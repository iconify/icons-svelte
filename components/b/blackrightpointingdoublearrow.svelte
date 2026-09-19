<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu5b3g62n.css';
import '../../css/l/lkpw8_1oe.css';
import '../../css/x/xjz9e4p7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cu5b3g62n"/><path class="lkpw8_1oe"/><path class="xjz9e4p7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackrightpointingdoublearrow" {...props}></Icon>
