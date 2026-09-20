<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pphbv6qxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pphbv6qxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bell" {...props}></Icon>
