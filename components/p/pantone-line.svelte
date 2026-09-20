<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2e20tbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2e20tbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pantone-line" {...props}></Icon>
