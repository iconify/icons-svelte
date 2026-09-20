<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9rat2byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g9rat2byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:diamond-o" {...props}></Icon>
