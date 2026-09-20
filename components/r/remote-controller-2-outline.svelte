<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bs0tjfbcq.css';
import '../../css/r/rgxk9p1eb.css';
import '../../css/s/spt4_bc5z.css';
import '../../css/b/bin6o3y-j.css';
import '../../css/c/cr51c0lxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bs0tjfbcq"/><path class="rgxk9p1eb"/><path class="spt4_bc5z"/><path class="bin6o3y-j"/><path class="cr51c0lxq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:remote-controller-2-outline" {...props}></Icon>
