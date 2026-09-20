<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omopg9mhb.css';
import '../../css/n/ngs9tw2ne.css';
import '../../css/i/id5d7cbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="omopg9mhb"/><path class="ngs9tw2ne"/><path class="id5d7cbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-text-format-2" {...props}></Icon>
