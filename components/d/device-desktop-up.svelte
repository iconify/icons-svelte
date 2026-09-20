<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hssyr4yeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hssyr4yeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-up" {...props}></Icon>
