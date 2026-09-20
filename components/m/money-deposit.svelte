<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blwbkzb0w.css';
import '../../css/r/rh4s4ac8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="blwbkzb0w"/><path class="rh4s4ac8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:money-deposit" {...props}></Icon>
