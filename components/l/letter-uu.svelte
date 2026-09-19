<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oovtryb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oovtryb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-uu" {...props}></Icon>
