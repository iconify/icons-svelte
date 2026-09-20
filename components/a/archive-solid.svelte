<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3343x6iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3343x6iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:archive-solid" {...props}></Icon>
