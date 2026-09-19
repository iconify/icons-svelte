<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj114hbbv.css';
import '../../css/n/n6f1xofwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jj114hbbv"/><path class="n6f1xofwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-journal" {...props}></Icon>
