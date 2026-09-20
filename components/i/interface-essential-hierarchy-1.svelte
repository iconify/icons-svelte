<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1verwbwl.css';
import '../../css/g/g2r24b_3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f1verwbwl"/><path class="g2r24b_3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-hierarchy-1" {...props}></Icon>
