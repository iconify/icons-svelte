<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlg1h8epy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vlg1h8epy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-security" {...props}></Icon>
