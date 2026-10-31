<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv6fvq_qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rv6fvq_qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-bunny-gloss" {...props}></Icon>
