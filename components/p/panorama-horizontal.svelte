<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5_ntkb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v5_ntkb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:panorama-horizontal" {...props}></Icon>
