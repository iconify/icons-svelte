<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/n/n4q3579np.css';
import '../../css/c/c2d8dlb9m.css';
import '../../css/p/p8rswpbhk.css';
import '../../css/n/n0kma69zb.css';
import '../../css/i/i8dwev7ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="n4q3579np"/><path class="c2d8dlb9m"/><path class="p8rswpbhk"/><path class="n0kma69zb"/><path class="i8dwev7ug"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:as" {...props}></Icon>
