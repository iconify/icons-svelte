<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/l2mflcm2v.css';
import '../../css/g/g2xclxbug.css';
import '../../css/j/jkj5y8biz.css';
import '../../css/m/my7poevrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="l2mflcm2v wm-deco"/><path class="g2xclxbug wm-deco"/><path class="jkj5y8biz wm-k"/><path class="my7poevrw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:film-blueprint" {...props}></Icon>
