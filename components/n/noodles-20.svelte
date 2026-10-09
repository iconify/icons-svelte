<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa0mk_bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fa0mk_bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:noodles-20" {...props}></Icon>
