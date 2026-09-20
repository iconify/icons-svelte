<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmnazo_5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmnazo_5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:camera-plus" {...props}></Icon>
