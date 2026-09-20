<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndq1rxbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ndq1rxbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:handle-corner" {...props}></Icon>
