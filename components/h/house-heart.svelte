<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtm7f4y8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtm7f4y8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-heart" {...props}></Icon>
