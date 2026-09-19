<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unk65rxam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="unk65rxam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-engineering-systems-design-rhapsody" {...props}></Icon>
