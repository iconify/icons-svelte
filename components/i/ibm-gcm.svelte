<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxujzib5b.css';
import '../../css/o/okc6ec79j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jxujzib5b"/><path class="okc6ec79j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-gcm" {...props}></Icon>
