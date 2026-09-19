<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j44066b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j44066b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:notes-fill-16" {...props}></Icon>
