<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3_-5u1bi.css';
import '../../css/s/sb5p6obzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3_-5u1bi"/><path class="sb5p6obzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:calendar-3-bold" {...props}></Icon>
