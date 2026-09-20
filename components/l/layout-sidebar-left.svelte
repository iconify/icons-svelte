<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibu1jey3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibu1jey3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:layout-sidebar-left" {...props}></Icon>
