<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op8cfac-b.css';
import '../../css/f/fc86yboyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="op8cfac-b"/><path class="fc86yboyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:bald" {...props}></Icon>
