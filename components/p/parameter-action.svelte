<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nof7r7bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nof7r7bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:parameter-action" {...props}></Icon>
