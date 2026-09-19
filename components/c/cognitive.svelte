<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd_z2mmch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jd_z2mmch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cognitive" {...props}></Icon>
