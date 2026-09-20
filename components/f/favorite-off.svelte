<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqr-xj2wz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqr-xj2wz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:favorite-off" {...props}></Icon>
