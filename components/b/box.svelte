<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0xc77b1s.css';
import '../../css/v/v8t77j0kk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l0xc77b1s"/><path class="v8t77j0kk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:box" {...props}></Icon>
