<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miu5gabev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="miu5gabev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:covid-off-line" {...props}></Icon>
