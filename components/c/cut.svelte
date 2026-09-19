<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2ot29b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s2ot29b8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:cut" {...props}></Icon>
