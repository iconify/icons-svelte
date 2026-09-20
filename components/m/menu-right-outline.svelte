<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asu8uubvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asu8uubvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:menu-right-outline" {...props}></Icon>
