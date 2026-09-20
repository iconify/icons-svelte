<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pri68xb4e.css';
import '../../css/i/i2a0yabqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pri68xb4e"/><path class="i2a0yabqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cal-com-dark" {...props}></Icon>
