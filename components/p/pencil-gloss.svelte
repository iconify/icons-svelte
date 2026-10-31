<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4vbq9aig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4vbq9aig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pencil-gloss" {...props}></Icon>
