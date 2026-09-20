<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_w8m9d2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e_w8m9d2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:info" {...props}></Icon>
