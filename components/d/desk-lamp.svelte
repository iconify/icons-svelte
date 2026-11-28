<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzy2t0_hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzy2t0_hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:desk-lamp" {...props}></Icon>
