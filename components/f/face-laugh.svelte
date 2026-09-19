<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/til_wmyiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="til_wmyiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-laugh" {...props}></Icon>
