<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khu5r_tqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khu5r_tqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cube-solid" {...props}></Icon>
