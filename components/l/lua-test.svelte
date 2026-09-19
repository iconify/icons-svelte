<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o58hkebvg.css';
import '../../css/b/bko_cabbv.css';
import '../../css/j/j-npdpb0r.css';
import '../../css/e/eggq918-u.css';
import '../../css/v/vkxno4e2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="o58hkebvg"><path class="bko_cabbv"/><g class="j-npdpb0r"><path class="eggq918-u"/><path class="vkxno4e2f"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:lua-test" {...props}></Icon>
