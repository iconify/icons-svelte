<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0l9w0esz.css';
import '../../css/d/da7n23beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a0l9w0esz"/><path class="da7n23beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:markstack-light" {...props}></Icon>
