<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oydxdbtff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oydxdbtff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:netflix-fill" {...props}></Icon>
