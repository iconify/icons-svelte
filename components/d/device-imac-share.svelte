<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6qm1-1vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6qm1-1vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-share" {...props}></Icon>
