<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgmv_dbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wgmv_dbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:grid-big" {...props}></Icon>
