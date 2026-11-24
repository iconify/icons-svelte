<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b717o-bps.css';
import '../../css/g/gigg_sbik.css';
import '../../css/s/supxy0b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b717o-bps"/><path class="gigg_sbik"/><path class="supxy0b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:house-arrow-left-filled" {...props}></Icon>
