<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbh3twb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sbh3twb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-spiral" {...props}></Icon>
