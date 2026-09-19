<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb-jdcqqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kb-jdcqqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:globe-private" {...props}></Icon>
