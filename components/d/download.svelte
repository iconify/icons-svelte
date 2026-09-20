<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm0nqy8gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mm0nqy8gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:download" {...props}></Icon>
