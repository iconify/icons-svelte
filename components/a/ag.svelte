<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x6-u63tpe.css';
import '../../css/s/s-f1sxbzj.css';
import '../../css/n/ngw05cc0t.css';
import '../../css/i/ijey5tl3d.css';
import '../../css/u/uebyq5hhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="x6-u63tpe"/><path clip-rule="evenodd" class="s-f1sxbzj"/><path class="ngw05cc0t"/><path class="ijey5tl3d"/><path clip-rule="evenodd" class="uebyq5hhe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:ag" {...props}></Icon>
