<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cedsxbbuw.css';
import '../../css/v/vvu8i0bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cedsxbbuw"/><path class="vvu8i0bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:coin-piles" {...props}></Icon>
