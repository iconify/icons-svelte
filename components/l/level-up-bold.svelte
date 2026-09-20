<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7h6zc0to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q7h6zc0to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:level-up-bold" {...props}></Icon>
