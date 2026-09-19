<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg-t_fezd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kg-t_fezd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:h1-20-solid" {...props}></Icon>
