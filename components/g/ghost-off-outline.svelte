<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slc-01ydo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slc-01ydo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ghost-off-outline" {...props}></Icon>
