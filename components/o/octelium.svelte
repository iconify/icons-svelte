<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we9u1gzwf.css';
import '../../css/j/jf-7ccbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="we9u1gzwf"/><path class="jf-7ccbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:octelium" {...props}></Icon>
