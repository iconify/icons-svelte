<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wex2-nbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wex2-nbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:cog" {...props}></Icon>
