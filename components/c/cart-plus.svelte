<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvyy595xw.css';
import '../../css/t/t2k1y2acb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvyy595xw"/><path class="t2k1y2acb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cart-plus" {...props}></Icon>
