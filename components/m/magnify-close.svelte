<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcw2n9bxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcw2n9bxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:magnify-close" {...props}></Icon>
