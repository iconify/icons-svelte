<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8ah0bs5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d8ah0bs5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:border-bottom" {...props}></Icon>
