<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz7ar6_-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz7ar6_-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:portrait" {...props}></Icon>
