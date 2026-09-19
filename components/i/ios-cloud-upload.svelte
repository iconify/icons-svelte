<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2vigwbeq.css';
import '../../css/j/jwwa9k2ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g2vigwbeq"/><path class="jwwa9k2ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cloud-upload" {...props}></Icon>
