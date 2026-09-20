<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_pr8ov3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="u_pr8ov3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:religious-shinto-11" {...props}></Icon>
