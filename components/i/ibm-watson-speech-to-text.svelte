<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttidz-lwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ttidz-lwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watson-speech-to-text" {...props}></Icon>
