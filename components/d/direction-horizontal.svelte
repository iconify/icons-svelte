<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe_z-t4nf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe_z-t4nf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:direction-horizontal" {...props}></Icon>
