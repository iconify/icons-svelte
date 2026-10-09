<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az4cwab1h.css';
import '../../css/o/ouobwmwuo.css';
import '../../css/q/qing99btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="az4cwab1h"/><path class="ouobwmwuo"/><path class="qing99btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-low-20" {...props}></Icon>
