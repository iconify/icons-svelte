<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6bka3n5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6bka3n5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:brightness" {...props}></Icon>
