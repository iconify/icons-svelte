<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b43v05bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b43v05bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:radar-enhanced" {...props}></Icon>
