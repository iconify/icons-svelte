<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flcb-acfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flcb-acfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:oshkosh" {...props}></Icon>
