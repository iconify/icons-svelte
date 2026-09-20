<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scn4tpb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scn4tpb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrowhead-up-expressive" {...props}></Icon>
