<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfiw6xiub.css';
import '../../css/m/mfnnmcbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zfiw6xiub"/><path class="mfnnmcbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:condition-point" {...props}></Icon>
