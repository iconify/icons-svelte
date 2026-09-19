<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_kynueps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x_kynueps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:model-builder" {...props}></Icon>
