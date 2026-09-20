<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjlcgh0pj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjlcgh0pj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:content-paste" {...props}></Icon>
