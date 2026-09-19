<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oupseqp3w.css';
import '../../css/g/g_ko1zbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oupseqp3w"/><path class="g_ko1zbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cell-tower" {...props}></Icon>
