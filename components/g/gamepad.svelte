<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5nkwoc8d.css';
import '../../css/i/i-1cn8fad.css';
import '../../css/p/ptk9v2bpu.css';
import '../../css/j/j9jczgbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k x5nkwoc8d"/><path class="i-1cn8fad wm-k"/><path class="ptk9v2bpu wm-a"/><path class="j9jczgbif wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:gamepad" {...props}></Icon>
