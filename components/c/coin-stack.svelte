<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_71-fb8o.css';
import '../../css/g/gg06_sb0j.css';
import '../../css/u/ut5psuaky.css';
import '../../css/p/pz2zo8bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_71-fb8o"/><path class="gg06_sb0j"/><path class="ut5psuaky"/><path class="pz2zo8bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:coin-stack" {...props}></Icon>
