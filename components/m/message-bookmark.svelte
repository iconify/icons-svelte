<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oma-vc_qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oma-vc_qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:message-bookmark" {...props}></Icon>
