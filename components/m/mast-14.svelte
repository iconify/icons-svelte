<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhb58tbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="nhb58tbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:mast-14" {...props}></Icon>
