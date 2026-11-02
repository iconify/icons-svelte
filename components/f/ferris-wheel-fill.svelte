<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut_z27wac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ut_z27wac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ferris-wheel-fill" {...props}></Icon>
