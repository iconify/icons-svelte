<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu7q4ib2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eu7q4ib2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-box-gabled-building-with-window" {...props}></Icon>
