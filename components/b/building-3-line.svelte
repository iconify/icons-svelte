<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr60ftpbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr60ftpbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:building-3-line" {...props}></Icon>
