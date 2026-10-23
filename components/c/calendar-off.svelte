<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyo_xixvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyo_xixvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-off" {...props}></Icon>
