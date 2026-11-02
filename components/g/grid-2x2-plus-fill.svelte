<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_yxm_tx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gp_yxm_tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grid-2x2-plus-fill" {...props}></Icon>
