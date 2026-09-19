<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mitnc4beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mitnc4beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-knowledge-catalog-premium" {...props}></Icon>
