<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzs041baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzs041baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:postage-stamp" {...props}></Icon>
