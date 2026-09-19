<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq9p_gbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dq9p_gbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:girl-confused" {...props}></Icon>
