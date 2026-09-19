<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzf-sabyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yzf-sabyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-webmethods-managed-file-transfer" {...props}></Icon>
