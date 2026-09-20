<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txz21fopn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txz21fopn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:keyboard" {...props}></Icon>
