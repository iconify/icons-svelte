<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q33dsdzhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="q33dsdzhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bookmark-simple-slash-light" {...props}></Icon>
