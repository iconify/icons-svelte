<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0sogrumm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j0sogrumm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:comment-alt" {...props}></Icon>
