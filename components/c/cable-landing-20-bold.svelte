<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag0bvbcgf.css';
import '../../css/g/gampl1_hh.css';
import '../../css/b/b0z-l4tfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ag0bvbcgf"/><path class="gampl1_hh"/><path class="b0z-l4tfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-landing-20-bold" {...props}></Icon>
