<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec08a_b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ec08a_b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:binoculars-gloss" {...props}></Icon>
