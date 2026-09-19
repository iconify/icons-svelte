<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8u_vxo6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8u_vxo6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:cube-transparent" {...props}></Icon>
