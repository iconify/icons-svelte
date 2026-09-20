<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhf8m9a1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhf8m9a1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-from-grid" {...props}></Icon>
