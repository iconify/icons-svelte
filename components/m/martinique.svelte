<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/socnatb_v.css';
import '../../css/o/oyw6nnb2s.css';
import '../../css/x/xh-ojeezs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="socnatb_v"/><path class="oyw6nnb2s"/><path class="xh-ojeezs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:martinique" {...props}></Icon>
