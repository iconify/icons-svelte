<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-oux7sxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-oux7sxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-alarm-snooze" {...props}></Icon>
