<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6bi2lk6s.css';
import '../../css/x/xloc_vq6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t6bi2lk6s"/><path class="xloc_vq6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:fastfood" {...props}></Icon>
