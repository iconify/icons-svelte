<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6dumf67y.css';
import '../../css/f/fvfljrbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j6dumf67y"/><path class="fvfljrbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-filter" {...props}></Icon>
