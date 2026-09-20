<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxw2sxb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qxw2sxb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:compose" {...props}></Icon>
