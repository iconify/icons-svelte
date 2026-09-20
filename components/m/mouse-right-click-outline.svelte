<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn5qy_bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dn5qy_bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mouse-right-click-outline" {...props}></Icon>
