<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixx4r3bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ixx4r3bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-model-context-protocol" {...props}></Icon>
