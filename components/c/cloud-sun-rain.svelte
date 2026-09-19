<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkiso9bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkiso9bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-sun-rain" {...props}></Icon>
