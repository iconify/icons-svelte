<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joz7wcc-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="joz7wcc-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-end-fill-12" {...props}></Icon>
