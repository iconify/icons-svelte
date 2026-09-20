<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8y6igb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x8y6igb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:add-dock" {...props}></Icon>
