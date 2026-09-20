<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh7wwmh2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rh7wwmh2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:food-truck-event-fair-remix" {...props}></Icon>
