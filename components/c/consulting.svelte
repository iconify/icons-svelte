<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic87zvbqj.css';
import '../../css/h/h-plcb8jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ic87zvbqj"/><path class="h-plcb8jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:consulting" {...props}></Icon>
