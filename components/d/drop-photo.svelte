<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3kj9tbpq.css';
import '../../css/c/cat22_54h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a3kj9tbpq"/><path class="cat22_54h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:drop-photo" {...props}></Icon>
