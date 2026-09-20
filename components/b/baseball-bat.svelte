<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i92lqpi-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i92lqpi-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:baseball-bat" {...props}></Icon>
