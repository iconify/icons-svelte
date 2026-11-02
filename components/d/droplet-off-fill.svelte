<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7weevkfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7weevkfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:droplet-off-fill" {...props}></Icon>
