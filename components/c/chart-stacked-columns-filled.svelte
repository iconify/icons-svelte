<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv82l7bbi.css';
import '../../css/h/h4r_0kb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv82l7bbi"/><path class="h4r_0kb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chart-stacked-columns-filled" {...props}></Icon>
