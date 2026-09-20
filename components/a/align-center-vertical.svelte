<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkbx_wbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkbx_wbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-center-vertical" {...props}></Icon>
