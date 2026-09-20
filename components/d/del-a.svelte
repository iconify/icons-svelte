<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8asgzqny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i8asgzqny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:del-a" {...props}></Icon>
