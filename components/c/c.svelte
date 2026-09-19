<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnv9l0mjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dnv9l0mjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:c" {...props}></Icon>
