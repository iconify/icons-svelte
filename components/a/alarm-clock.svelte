<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u60-i8alj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="u60-i8alj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:alarm-clock" {...props}></Icon>
