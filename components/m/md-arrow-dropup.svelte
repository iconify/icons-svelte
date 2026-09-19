<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr0vp1bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cr0vp1bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-arrow-dropup" {...props}></Icon>
