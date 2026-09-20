<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_nq73a6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w_nq73a6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:hourglass-empty" {...props}></Icon>
