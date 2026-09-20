<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5tmu2-3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b5tmu2-3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:crown" {...props}></Icon>
