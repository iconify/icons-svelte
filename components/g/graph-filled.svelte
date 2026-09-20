<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csuic1o1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csuic1o1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:graph-filled" {...props}></Icon>
