<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dloswtbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dloswtbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:road-branches" {...props}></Icon>
