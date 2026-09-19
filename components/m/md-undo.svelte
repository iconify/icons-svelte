<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucl-n6z2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ucl-n6z2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-undo" {...props}></Icon>
