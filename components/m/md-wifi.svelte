<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x04kdffme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x04kdffme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-wifi" {...props}></Icon>
