<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwl4a6cod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwl4a6cod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-circle" {...props}></Icon>
