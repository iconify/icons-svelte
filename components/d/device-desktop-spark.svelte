<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkg5xlu5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkg5xlu5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-spark" {...props}></Icon>
