<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ird4xpdhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ird4xpdhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hulu" {...props}></Icon>
