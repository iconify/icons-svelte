<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7aotbbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n7aotbbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:buy" {...props}></Icon>
