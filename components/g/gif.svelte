<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7ywibcrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u7ywibcrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:gif" {...props}></Icon>
