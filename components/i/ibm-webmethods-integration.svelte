<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkkun1bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wkkun1bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-webmethods-integration" {...props}></Icon>
