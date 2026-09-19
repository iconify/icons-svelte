<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow83bgbqz.css';
import '../../css/v/vg49bdvkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ow83bgbqz"/><path class="vg49bdvkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-close-circle-outline" {...props}></Icon>
