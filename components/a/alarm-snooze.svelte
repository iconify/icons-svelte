<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ectql4bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ectql4bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alarm-snooze" {...props}></Icon>
