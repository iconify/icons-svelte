<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu-ss8biv.css';
import '../../css/z/zg21q53ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hu-ss8biv"/><path class="zg21q53ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watson-natural-language-understanding" {...props}></Icon>
