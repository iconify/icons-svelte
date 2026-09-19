<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq18vxb1u.css';
import '../../css/g/g7j88-bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uq18vxb1u"/><path class="g7j88-bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:accumulation-precipitation" {...props}></Icon>
