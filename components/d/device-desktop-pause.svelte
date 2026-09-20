<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar3k3kbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar3k3kbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-pause" {...props}></Icon>
