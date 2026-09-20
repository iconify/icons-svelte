<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2oaplh7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2oaplh7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-j-circle-outline" {...props}></Icon>
