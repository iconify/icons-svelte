<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk-do6bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fk-do6bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-down-above-arrow-right-beside-arrow-left-above-arrow-up" {...props}></Icon>
