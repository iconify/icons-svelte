<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfyk-ub-n.css';
import '../../css/h/hbzul7b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="xfyk-ub-n"/><path class="hbzul7b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:rewind-ten" {...props}></Icon>
