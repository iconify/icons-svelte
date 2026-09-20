<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmz6kf.css';
import '../../css/d/d-jarxnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmz6kf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:close-to-menu-transition" {...props}></Icon>
