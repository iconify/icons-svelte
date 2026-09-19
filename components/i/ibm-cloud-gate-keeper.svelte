<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6dy7ob-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z6dy7ob-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-gate-keeper" {...props}></Icon>
