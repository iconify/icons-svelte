<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/s79qgjdvm.css';
import '../../css/p/p49qakbea.css';
import '../../css/l/lifkejbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="s79qgjdvm"/><path class="p49qakbea"/><path class="lifkejbvr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:briefcase-dollar" {...props}></Icon>
