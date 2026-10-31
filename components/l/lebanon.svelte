<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7ephwb-o.css';
import '../../css/v/v_devvdob.css';
import '../../css/f/fwasz7buv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="x7ephwb-o"/><path class="v_devvdob"/><path class="fwasz7buv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:lebanon" {...props}></Icon>
