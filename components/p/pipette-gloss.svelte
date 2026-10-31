<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypvqe6-il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k ypvqe6-il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pipette-gloss" {...props}></Icon>
