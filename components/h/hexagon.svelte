<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrjor5bbf.css';
import '../../css/n/njn_aqw9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrjor5bbf wm-k"/><path class="njn_aqw9z wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:hexagon" {...props}></Icon>
