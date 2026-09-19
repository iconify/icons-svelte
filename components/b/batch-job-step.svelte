<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek4yftbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ek4yftbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:batch-job-step" {...props}></Icon>
