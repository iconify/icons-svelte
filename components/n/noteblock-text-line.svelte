<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m17loqb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m17loqb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:noteblock-text-line" {...props}></Icon>
