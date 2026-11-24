<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikzgpudrt.css';
import '../../css/d/dxc9wabla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikzgpudrt"/><path class="dxc9wabla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bell-check-filled" {...props}></Icon>
