<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzf5q85kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uzf5q85kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:hardware-tablet" {...props}></Icon>
