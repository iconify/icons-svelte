<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi_sajbdp.css';
import '../../css/x/xk7ze-bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":16};
const content = `<path class="hi_sajbdp"/><path class="xk7ze-bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:images" {...props}></Icon>
