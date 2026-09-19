<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfxii2bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bfxii2bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hand-scissors" {...props}></Icon>
