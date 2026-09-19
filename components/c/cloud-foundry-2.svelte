<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct5dzobis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ct5dzobis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-foundry-2" {...props}></Icon>
