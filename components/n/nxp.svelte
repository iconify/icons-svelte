<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir472ac2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir472ac2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nxp" {...props}></Icon>
