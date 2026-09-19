<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv7zpptfp.css';
import '../../css/x/xnpc5acoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gv7zpptfp"/><path class="xnpc5acoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:nx" {...props}></Icon>
