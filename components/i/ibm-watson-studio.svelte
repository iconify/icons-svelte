<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntkv2lbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ntkv2lbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watson-studio" {...props}></Icon>
