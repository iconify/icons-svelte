<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvoo6thzj.css';
import '../../css/j/jz9026bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="jvoo6thzj"/><circle class="jz9026bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:musical-score" {...props}></Icon>
