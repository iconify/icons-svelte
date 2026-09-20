<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl6aybotc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl6aybotc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-long-left" {...props}></Icon>
