<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgp1p-jmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qgp1p-jmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-brush" {...props}></Icon>
