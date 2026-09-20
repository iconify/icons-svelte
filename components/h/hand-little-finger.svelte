<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m26zf4yei.css';
import '../../css/o/odibfhbmi.css';
import '../../css/c/czl7urd3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m26zf4yei"/><path class="odibfhbmi"/><path class="czl7urd3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:hand-little-finger" {...props}></Icon>
