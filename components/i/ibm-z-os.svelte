<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkc89nbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jkc89nbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-z-os" {...props}></Icon>
