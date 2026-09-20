<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_fr24-nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_fr24-nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-x" {...props}></Icon>
