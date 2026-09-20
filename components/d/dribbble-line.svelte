<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3r8zszzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3r8zszzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dribbble-line" {...props}></Icon>
