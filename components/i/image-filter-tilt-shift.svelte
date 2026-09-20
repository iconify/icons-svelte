<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzsx4hbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzsx4hbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-filter-tilt-shift" {...props}></Icon>
