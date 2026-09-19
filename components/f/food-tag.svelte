<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mme__qbhi.css';
import '../../css/a/as3fepoct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mme__qbhi"/><circle class="as3fepoct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:food-tag" {...props}></Icon>
