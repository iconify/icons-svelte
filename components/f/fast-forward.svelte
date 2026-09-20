<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghtige71w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ghtige71w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:fast-forward" {...props}></Icon>
