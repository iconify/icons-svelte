<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-a3-_mce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-a3-_mce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:av-timer" {...props}></Icon>
