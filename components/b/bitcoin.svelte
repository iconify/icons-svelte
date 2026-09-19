<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahus_ublf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahus_ublf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:bitcoin" {...props}></Icon>
