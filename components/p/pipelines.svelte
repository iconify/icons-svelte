<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okikuvbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="okikuvbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pipelines" {...props}></Icon>
