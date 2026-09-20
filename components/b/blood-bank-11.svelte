<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj3orgbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="rj3orgbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:blood-bank-11" {...props}></Icon>
