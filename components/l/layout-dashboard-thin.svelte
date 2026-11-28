<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk693vblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="wk693vblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:layout-dashboard-thin" {...props}></Icon>
