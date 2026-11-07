<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx9lmrblm.css';
import '../../css/p/p0tpqpbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx9lmrblm"/><path class="p0tpqpbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folders-bold-duotone" {...props}></Icon>
