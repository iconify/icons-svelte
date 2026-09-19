<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th6-23bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="th6-23bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:calendar-alt" {...props}></Icon>
