<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy5ym81zr.css';
import '../../css/z/z8k-y_stg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cy5ym81zr"/><path class="z8k-y_stg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:dns-services" {...props}></Icon>
