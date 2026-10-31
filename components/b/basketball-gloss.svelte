<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3sthvb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3sthvb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:basketball-gloss" {...props}></Icon>
