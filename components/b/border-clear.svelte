<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvvx_2iyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gvvx_2iyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:border-clear" {...props}></Icon>
