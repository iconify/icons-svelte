<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcf2c5nxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcf2c5nxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-navbar-filled" {...props}></Icon>
