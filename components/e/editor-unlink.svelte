<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnemedg5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jnemedg5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-unlink" {...props}></Icon>
