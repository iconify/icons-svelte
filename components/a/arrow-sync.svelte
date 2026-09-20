<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcli11bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcli11bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:arrow-sync" {...props}></Icon>
