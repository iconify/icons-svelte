<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2d_h3bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2d_h3bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:record-circle" {...props}></Icon>
