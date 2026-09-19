<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9ng2ub9o.css';
import '../../css/t/t2k1y2acb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9ng2ub9o"/><path class="t2k1y2acb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cart-x" {...props}></Icon>
