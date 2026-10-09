<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf5-4acxm.css';
import '../../css/b/beal5kb9o.css';
import '../../css/i/idlt776qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jf5-4acxm"/><path class="beal5kb9o"/><path class="idlt776qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:medal-20-bold" {...props}></Icon>
