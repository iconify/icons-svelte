<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqcjsdbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqcjsdbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:frame-forward" {...props}></Icon>
