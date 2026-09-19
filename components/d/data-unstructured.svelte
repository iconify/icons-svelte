<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0ku6lcmx.css';
import '../../css/l/lruer8ufr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o0ku6lcmx"/><path class="lruer8ufr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-unstructured" {...props}></Icon>
