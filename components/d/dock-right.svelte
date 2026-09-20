<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoutpwb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoutpwb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dock-right" {...props}></Icon>
