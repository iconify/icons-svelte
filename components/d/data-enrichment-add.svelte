<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipkul0x-y.css';
import '../../css/k/kprce0ijz.css';
import '../../css/x/x8r3bo3uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ipkul0x-y"/><path class="kprce0ijz"/><path class="x8r3bo3uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-enrichment-add" {...props}></Icon>
