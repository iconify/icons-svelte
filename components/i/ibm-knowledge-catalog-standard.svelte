<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czraaybyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="czraaybyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-knowledge-catalog-standard" {...props}></Icon>
