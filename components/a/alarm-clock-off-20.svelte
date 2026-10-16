<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9aiyrfai.css';
import '../../css/t/tubi0bbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i9aiyrfai"/><path class="tubi0bbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:alarm-clock-off-20" {...props}></Icon>
