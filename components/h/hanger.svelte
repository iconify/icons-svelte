<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl1raybud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl1raybud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hanger" {...props}></Icon>
