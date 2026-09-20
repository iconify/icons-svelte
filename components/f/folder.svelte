<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp2-5gq9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jp2-5gq9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:folder" {...props}></Icon>
