<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb8ibbc3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pb8ibbc3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:attribute-definition" {...props}></Icon>
