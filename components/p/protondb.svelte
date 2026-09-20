<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjvpp3bga.css';
import '../../css/d/dslthebzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hjvpp3bga"/><circle class="dslthebzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:protondb" {...props}></Icon>
