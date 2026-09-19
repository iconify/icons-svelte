<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky_ty42kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":16};
const content = `<path class="ky_ty42kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:menu2" {...props}></Icon>
