<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgissgbda.css';
import '../../css/t/t3fbyzb7o.css';
import '../../css/o/ont9fsbmp.css';
import '../../css/h/hvizvfbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgissgbda"/><path class="t3fbyzb7o"/><path class="ont9fsbmp"/><path class="hvizvfbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-pen-bold-duotone" {...props}></Icon>
