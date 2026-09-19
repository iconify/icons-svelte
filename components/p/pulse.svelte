<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<polyline points="1.75 8.25 4.25 8.25 6.25 3.75 9.75 12.25 11.75 8.25 14.25 8.25" class="hntgybcog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:pulse" {...props}></Icon>
