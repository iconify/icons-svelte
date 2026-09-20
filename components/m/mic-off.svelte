<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp9z05b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp9z05b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mic-off" {...props}></Icon>
