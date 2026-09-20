<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc9u30brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="jc9u30brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:comment-text" {...props}></Icon>
