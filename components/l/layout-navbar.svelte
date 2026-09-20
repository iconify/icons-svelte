<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbonpnbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbonpnbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-navbar" {...props}></Icon>
