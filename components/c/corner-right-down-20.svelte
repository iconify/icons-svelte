<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlocb6bmt.css';
import '../../css/d/dhj1chemz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dlocb6bmt"/><path class="dhj1chemz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-right-down-20" {...props}></Icon>
