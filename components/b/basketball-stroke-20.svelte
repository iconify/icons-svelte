<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnz67-bnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cnz67-bnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:basketball-stroke-20" {...props}></Icon>
