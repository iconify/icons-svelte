<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxmxt78rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zxmxt78rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grocy" {...props}></Icon>
