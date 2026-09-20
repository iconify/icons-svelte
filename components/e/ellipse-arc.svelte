<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz2uc7bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iz2uc7bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ellipse-arc" {...props}></Icon>
