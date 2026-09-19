<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrradhcvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1568,"height":1536};
const content = `<path class="qrradhcvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:backward" {...props}></Icon>
