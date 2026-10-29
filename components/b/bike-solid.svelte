<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7zp2bcpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7zp2bcpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bike-solid" {...props}></Icon>
