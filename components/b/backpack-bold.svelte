<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_f_qcc_q.css';
import '../../css/l/lp0dbjbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x_f_qcc_q"/><path class="lp0dbjbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:backpack-bold" {...props}></Icon>
