<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkdfvacrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hkdfvacrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-cursor-2-flat" {...props}></Icon>
