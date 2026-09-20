<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqu2uom8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lqu2uom8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:dollar" {...props}></Icon>
