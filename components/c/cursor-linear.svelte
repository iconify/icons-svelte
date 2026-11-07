<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp2vt5b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp2vt5b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cursor-linear" {...props}></Icon>
