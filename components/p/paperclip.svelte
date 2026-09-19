<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4djbg3cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x4djbg3cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:paperclip" {...props}></Icon>
