<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/api0k3bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="api0k3bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:menu-close" {...props}></Icon>
