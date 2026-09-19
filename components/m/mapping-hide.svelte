<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndyg946ck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ndyg946ck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mapping-hide" {...props}></Icon>
