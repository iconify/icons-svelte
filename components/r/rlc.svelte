<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ferdt9nin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ferdt9nin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:rlc" {...props}></Icon>
