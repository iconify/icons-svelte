<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq_q15z3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="qq_q15z3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:guilded" {...props}></Icon>
