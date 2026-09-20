<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmvy9pb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="lmvy9pb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:coin-stack" {...props}></Icon>
