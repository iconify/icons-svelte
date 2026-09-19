<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0j0zhb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m0j0zhb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-pie-filled" {...props}></Icon>
