<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p-ipkgb1f.css';
import '../../css/r/r-zsl_btv.css';
import '../../css/b/bevhxabeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p-ipkgb1f"/><path class="r-zsl_btv"/><path class="bevhxabeh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:music-note-plus-solid" {...props}></Icon>
