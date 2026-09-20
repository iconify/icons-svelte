<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-gufo90d.css';
import '../../css/v/vvd0k01le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j-gufo90d"/><path class="vvd0k01le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quick-reference" {...props}></Icon>
