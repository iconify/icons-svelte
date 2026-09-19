<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpkla4bye.css';
import '../../css/l/lvwmqz7ny.css';
import '../../css/o/otefzfpii.css';
import '../../css/d/dy1rfcq1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cpkla4bye"/><path class="lvwmqz7ny"/><path class="otefzfpii"/><path class="dy1rfcq1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:qr-scanner" {...props}></Icon>
