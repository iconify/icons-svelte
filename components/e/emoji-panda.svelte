<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxwr1k8hq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxwr1k8hq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoji-panda" {...props}></Icon>
