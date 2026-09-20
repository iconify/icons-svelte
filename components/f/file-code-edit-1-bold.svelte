<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8jy0fbhv.css';
import '../../css/f/f76v0rbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8jy0fbhv"/><path class="f76v0rbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:file-code-edit-1-bold" {...props}></Icon>
