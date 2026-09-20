<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkyb1huxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rkyb1huxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:level-left" {...props}></Icon>
