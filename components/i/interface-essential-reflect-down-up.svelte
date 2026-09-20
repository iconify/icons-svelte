<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiekhvbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fiekhvbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-reflect-down-up" {...props}></Icon>
