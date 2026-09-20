<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdk2ryvgs.css';
import '../../css/o/oxo9nw_dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdk2ryvgs"/><path class="oxo9nw_dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ibat" {...props}></Icon>
