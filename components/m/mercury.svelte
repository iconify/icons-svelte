<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs61bmfjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hs61bmfjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mercury" {...props}></Icon>
