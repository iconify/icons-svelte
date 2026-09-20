<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwlb_qanr.css';
import '../../css/z/zt-7pdbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="jwlb_qanr"/><path class="zt-7pdbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:photos" {...props}></Icon>
