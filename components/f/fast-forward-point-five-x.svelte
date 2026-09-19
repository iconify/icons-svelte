<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrv_3ebjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qrv_3ebjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:fast-forward-point-five-x" {...props}></Icon>
