<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khc1gzhjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khc1gzhjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-tasks" {...props}></Icon>
