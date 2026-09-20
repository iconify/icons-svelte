<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imt9l1hvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="imt9l1hvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:chevron-circle-down" {...props}></Icon>
