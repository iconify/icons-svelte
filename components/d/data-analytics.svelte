<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqrep7bti.css';
import '../../css/g/g60lgdcxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vqrep7bti"/><path class="g60lgdcxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-analytics" {...props}></Icon>
