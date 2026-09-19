<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_t27sw-g.css';
import '../../css/x/x4c4cxb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_t27sw-g"/><path class="x4c4cxb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:lemon" {...props}></Icon>
