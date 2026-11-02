<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz3i1ib_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz3i1ib_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:box-2-fill" {...props}></Icon>
