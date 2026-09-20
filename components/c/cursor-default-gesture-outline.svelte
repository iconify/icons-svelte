<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce1h9l8wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce1h9l8wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cursor-default-gesture-outline" {...props}></Icon>
