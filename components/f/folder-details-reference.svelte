<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy1qi8xwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gy1qi8xwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:folder-details-reference" {...props}></Icon>
