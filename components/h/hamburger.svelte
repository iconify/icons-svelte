<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc9rh9xuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pc9rh9xuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:hamburger" {...props}></Icon>
