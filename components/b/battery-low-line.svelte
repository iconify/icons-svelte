<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hao-mcclc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hao-mcclc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:battery-low-line" {...props}></Icon>
