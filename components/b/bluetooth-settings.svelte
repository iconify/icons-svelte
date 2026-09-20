<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls1og1b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls1og1b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bluetooth-settings" {...props}></Icon>
