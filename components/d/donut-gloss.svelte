<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1c4_xzki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1c4_xzki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:donut-gloss" {...props}></Icon>
