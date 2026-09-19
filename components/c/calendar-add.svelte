<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdv_6bbog.css';
import '../../css/i/iz2obhzwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mdv_6bbog"/><path class="iz2obhzwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:calendar-add" {...props}></Icon>
