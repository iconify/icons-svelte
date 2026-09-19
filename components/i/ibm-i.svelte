<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkkhz-2jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tkkhz-2jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-i" {...props}></Icon>
