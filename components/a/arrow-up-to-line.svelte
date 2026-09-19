<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt__-0brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nt__-0brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-up-to-line" {...props}></Icon>
