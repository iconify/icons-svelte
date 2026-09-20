<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2fm2ws7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x2fm2ws7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:css3-alt" {...props}></Icon>
