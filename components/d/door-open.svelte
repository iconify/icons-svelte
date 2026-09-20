<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm46ofb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm46ofb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:door-open" {...props}></Icon>
