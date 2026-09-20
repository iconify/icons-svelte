<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrr3flboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrr3flboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-right5" {...props}></Icon>
