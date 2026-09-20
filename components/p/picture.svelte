<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irfjh1x1u.css';
import '../../css/y/y0k_xop1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="irfjh1x1u"/><path class="y0k_xop1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:picture" {...props}></Icon>
