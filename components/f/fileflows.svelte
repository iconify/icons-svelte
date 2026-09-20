<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be4hxabip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="be4hxabip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fileflows" {...props}></Icon>
