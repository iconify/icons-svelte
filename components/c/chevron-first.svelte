<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccm1rbbvi.css';
import '../../css/w/w_pcmxbnq.css';
import '../../css/f/funupzsqr.css';
import '../../css/b/bei80-zdg.css';
import '../../css/p/p8w35spzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccm1rbbvi wm-shadow"/><path class="w_pcmxbnq wm-k"/><path class="funupzsqr wm-k"/><path class="bei80-zdg wm-a"/><path class="p8w35spzu wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:chevron-first" {...props}></Icon>
