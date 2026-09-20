<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo3byjb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo3byjb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:earth-sphere-line" {...props}></Icon>
