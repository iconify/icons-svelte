<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epcpccbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="epcpccbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-tablet-portrait" {...props}></Icon>
