<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yilbywqwu.css';
import '../../css/r/rgoffbnwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yilbywqwu"/><path class="rgoffbnwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openvas-light" {...props}></Icon>
