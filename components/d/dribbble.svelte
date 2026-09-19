<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w__hynbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":440};
const content = `<path class="w__hynbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:dribbble" {...props}></Icon>
