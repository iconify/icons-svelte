<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm_cfgbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="nm_cfgbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:replay-5" {...props}></Icon>
