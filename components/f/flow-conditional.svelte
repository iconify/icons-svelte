<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jphow5moh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jphow5moh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flow-conditional" {...props}></Icon>
