<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlzwmtb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlzwmtb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:chevrons-horizontal" {...props}></Icon>
