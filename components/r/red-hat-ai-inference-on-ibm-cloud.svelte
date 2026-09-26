<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8_e15b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q8_e15b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:red-hat-ai-inference-on-ibm-cloud" {...props}></Icon>
