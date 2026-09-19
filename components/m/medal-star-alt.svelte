<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xahhmbe9e.css';
import '../../css/o/op1eu4bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xahhmbe9e"/><path class="op1eu4bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:medal-star-alt" {...props}></Icon>
