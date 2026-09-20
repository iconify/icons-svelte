<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxi_nimou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxi_nimou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ipfs" {...props}></Icon>
