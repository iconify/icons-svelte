<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4sx92bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="k4sx92bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:oracle-icon" {...props}></Icon>
