<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laf-l4e5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="laf-l4e5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-gamepad-3" {...props}></Icon>
