<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujqjk4b9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ujqjk4b9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:html-reference" {...props}></Icon>
