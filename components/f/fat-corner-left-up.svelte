<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi91_ui2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi91_ui2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fat-corner-left-up" {...props}></Icon>
