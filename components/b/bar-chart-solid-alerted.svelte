<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca9vsolul.css';
import '../../css/e/egbtnbclf.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="ca9vsolul clr-i-solid--alerted clr-i-solid-path-1--alerted"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-2--alerted egbtnbclf"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:bar-chart-solid-alerted" {...props}></Icon>
