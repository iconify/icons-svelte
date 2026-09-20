<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzd0tlb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dzd0tlb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:framer-logo" {...props}></Icon>
