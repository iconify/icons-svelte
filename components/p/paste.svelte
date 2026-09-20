<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnw7i4b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fnw7i4b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:paste" {...props}></Icon>
