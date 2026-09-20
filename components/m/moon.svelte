<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di4rr1_9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="di4rr1_9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:moon" {...props}></Icon>
