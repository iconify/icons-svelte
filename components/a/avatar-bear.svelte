<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/lim_lesma.css';
import '../../css/p/p8or_gjla.css';
import '../../css/c/cfnmr-b-v.css';
import '../../css/w/wc08x_b5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="lim_lesma wm-shadow"/><path class="p8or_gjla wm-shadow"/><path class="cfnmr-b-v"/><path class="wc08x_b5p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:avatar-bear" {...props}></Icon>
