<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyaa1ib5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyaa1ib5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-search" {...props}></Icon>
