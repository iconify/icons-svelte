<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zihtko4od.css';
import '../../css/o/oalqs3ghm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zihtko4od"/><path class="oalqs3ghm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:rocket-stroke-20" {...props}></Icon>
