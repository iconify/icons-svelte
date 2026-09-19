<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puoqvkpln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="puoqvkpln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:copy-to-clipboard" {...props}></Icon>
