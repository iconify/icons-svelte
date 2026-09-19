<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot4szdbar.css';
import '../../css/n/niefumugv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ot4szdbar"/><path class="niefumugv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-analytics" {...props}></Icon>
