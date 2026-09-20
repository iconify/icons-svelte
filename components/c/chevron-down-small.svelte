<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu0r17e0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cu0r17e0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:chevron-down-small" {...props}></Icon>
