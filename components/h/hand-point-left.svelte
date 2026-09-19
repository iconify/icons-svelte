<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/keh4ghbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="keh4ghbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:hand-point-left" {...props}></Icon>
