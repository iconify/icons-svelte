<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elt0apgww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="elt0apgww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:future" {...props}></Icon>
