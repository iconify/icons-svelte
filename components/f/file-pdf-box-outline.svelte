<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f97e20-gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f97e20-gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-pdf-box-outline" {...props}></Icon>
