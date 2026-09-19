<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcbbnl92k.css';
import '../../css/r/r_38ooa_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcbbnl92k"/><path class="r_38ooa_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-down-left-stroke-circle" {...props}></Icon>
