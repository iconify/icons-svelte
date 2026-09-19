<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0h0z9bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v0h0z9bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-streamsets" {...props}></Icon>
