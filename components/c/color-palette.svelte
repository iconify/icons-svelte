<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrqeybr-c.css';
import '../../css/o/o1embaboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qrqeybr-c"/><path class="o1embaboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:color-palette" {...props}></Icon>
