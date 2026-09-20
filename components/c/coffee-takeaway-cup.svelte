<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1l9ex7qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="i1l9ex7qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:coffee-takeaway-cup" {...props}></Icon>
