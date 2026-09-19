<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s67jb_bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s67jb_bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:lock-unlocked" {...props}></Icon>
