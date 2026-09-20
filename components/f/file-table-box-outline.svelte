<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5g2j3bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5g2j3bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-table-box-outline" {...props}></Icon>
