<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxv23u_pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxv23u_pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cake-layered" {...props}></Icon>
