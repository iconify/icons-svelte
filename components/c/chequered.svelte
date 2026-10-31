<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmibc4bxr.css';
import '../../css/r/rbe48ab4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="nmibc4bxr"/><path class="rbe48ab4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:chequered" {...props}></Icon>
