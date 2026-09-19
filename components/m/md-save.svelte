<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl1mrtb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rl1mrtb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-save" {...props}></Icon>
