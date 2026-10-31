<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw9psdo5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw9psdo5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:presentation-gloss" {...props}></Icon>
