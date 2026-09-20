<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jet3vgb5x.css';
import '../../css/i/ija69877e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="jet3vgb5x"/><path class="ija69877e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:comments-reply" {...props}></Icon>
