<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj_f8hdiy.css';
import '../../css/x/x7_q-qb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hj_f8hdiy"/><path class="x7_q-qb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ansible-wordmark" {...props}></Icon>
