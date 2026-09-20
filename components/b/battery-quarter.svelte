<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmy8aob1i.css';
import '../../css/k/k743-oxfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cmy8aob1i"/><path clip-rule="evenodd" class="k743-oxfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-quarter" {...props}></Icon>
