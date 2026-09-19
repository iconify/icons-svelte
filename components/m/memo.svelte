<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrbckyotk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":675,"height":717};
const content = `<path class="rrbckyotk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:memo" {...props}></Icon>
