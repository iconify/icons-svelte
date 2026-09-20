<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b186tqo6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b186tqo6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:memorial-stone-with-latin-cross" {...props}></Icon>
