<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4l44vbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4l44vbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:lineicons" {...props}></Icon>
