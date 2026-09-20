<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcz0i0b6y.css';
import '../../css/b/b3uq48bmq.css';
import '../../css/c/clgcxl7va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="fcz0i0b6y"/><path class="b3uq48bmq"/><path class="clgcxl7va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:black-circle" {...props}></Icon>
