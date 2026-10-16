<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhcjdtn8d.css';
import '../../css/l/l8_-m635t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yhcjdtn8d"/><path class="l8_-m635t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-snooze-20" {...props}></Icon>
