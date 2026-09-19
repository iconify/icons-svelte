<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rljligbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rljligbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hand-pointing-left-01" {...props}></Icon>
