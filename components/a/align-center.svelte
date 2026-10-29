<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh4rqfpek.css';
import '../../css/l/luoocdwcm.css';
import '../../css/m/mrtpigbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh4rqfpek"/><path class="luoocdwcm"/><path class="mrtpigbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:align-center" {...props}></Icon>
