<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dltsm_4ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dltsm_4ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:circle-close" {...props}></Icon>
