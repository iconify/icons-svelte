<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd_9zuben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vd_9zuben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:circle-thin" {...props}></Icon>
