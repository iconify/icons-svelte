<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhj0e-blr.css';
import '../../css/e/etqe0ibeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zhj0e-blr"/><path clip-rule="evenodd" class="etqe0ibeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:cup-solid" {...props}></Icon>
