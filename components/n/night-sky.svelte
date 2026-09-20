<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4nvl3pqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4nvl3pqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:night-sky" {...props}></Icon>
