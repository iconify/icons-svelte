<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwyy-sbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uwyy-sbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ai-governance-lifecycle" {...props}></Icon>
