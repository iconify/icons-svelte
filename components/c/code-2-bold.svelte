<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a510ge4pz.css';
import '../../css/m/mnpe9tboq.css';
import '../../css/k/k324ub9yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a510ge4pz"/><path class="mnpe9tboq"/><path class="k324ub9yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-2-bold" {...props}></Icon>
