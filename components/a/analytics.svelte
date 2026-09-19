<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg14rmb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zg14rmb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:analytics" {...props}></Icon>
