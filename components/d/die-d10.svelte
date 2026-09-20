<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lamx9gjea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lamx9gjea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:die-d10" {...props}></Icon>
