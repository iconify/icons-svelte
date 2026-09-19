<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgjulrbun.css';
import '../../css/w/w558l_3fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rgjulrbun"/><path class="w558l_3fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-flash-off" {...props}></Icon>
