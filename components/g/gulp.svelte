<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv3dl_bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv3dl_bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gulp" {...props}></Icon>
