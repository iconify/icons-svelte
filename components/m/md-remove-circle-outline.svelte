<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow83bgbqz.css';
import '../../css/x/xti0nob1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ow83bgbqz"/><path class="xti0nob1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-remove-circle-outline" {...props}></Icon>
