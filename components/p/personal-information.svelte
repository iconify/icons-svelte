<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mvb3-tboc.css';
import '../../css/p/p2iw4076h.css';
import '../../css/u/ufu0pi29p.css';
import '../../css/c/cu6gj4bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mvb3-tboc"/><path class="p2iw4076h"/><path class="ufu0pi29p"/><path class="cu6gj4bai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:personal-information" {...props}></Icon>
