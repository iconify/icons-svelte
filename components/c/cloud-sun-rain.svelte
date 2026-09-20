<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktja0bbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktja0bbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cloud-sun-rain" {...props}></Icon>
