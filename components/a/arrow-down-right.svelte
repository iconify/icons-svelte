<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gn9jlpb0m.css';
import '../../css/w/wyqznsb4z.css';
import '../../css/e/eexuiebst.css';
import '../../css/t/tmqg3xbsd.css';
import '../../css/d/ddy94qblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gn9jlpb0m wm-deco"/><path class="wm-k wyqznsb4z"/><path class="eexuiebst wm-k"/><path class="tmqg3xbsd wm-k"/><path class="ddy94qblz wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-anime:arrow-down-right" {...props}></Icon>
