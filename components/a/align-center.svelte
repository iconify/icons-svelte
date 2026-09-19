<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4e1gyb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p4e1gyb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:align-center" {...props}></Icon>
