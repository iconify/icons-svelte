<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foexnebhq.css';
import '../../css/e/e_7r0xb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="foexnebhq"/><path class="e_7r0xb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:car-garage" {...props}></Icon>
