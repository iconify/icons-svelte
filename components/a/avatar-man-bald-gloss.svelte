<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz0aanbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mz0aanbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-man-bald-gloss" {...props}></Icon>
