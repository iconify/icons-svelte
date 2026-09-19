<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5-lgcc0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u5-lgcc0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:identification" {...props}></Icon>
