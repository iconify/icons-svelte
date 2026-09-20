<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v45t3ubcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v45t3ubcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:map-line" {...props}></Icon>
