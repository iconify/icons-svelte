<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae2_vkljg.css';
import '../../css/t/tubczkbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ae2_vkljg"/><path class="tubczkbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:notes" {...props}></Icon>
