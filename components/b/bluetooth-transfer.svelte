<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsfww-brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsfww-brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bluetooth-transfer" {...props}></Icon>
