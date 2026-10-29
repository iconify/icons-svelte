<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/r/r251e8b6n.css';
import '../../css/b/bzinr4bnh.css';
import '../../css/r/r1yzrf19m.css';
import '../../css/p/p8x8sgbum.css';
import '../../css/v/v7v_u0jql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="r251e8b6n wm-deco"/><path class="bzinr4bnh wm-deco"/><path class="r1yzrf19m wm-deco"/><path class="p8x8sgbum wm-k"/><path class="v7v_u0jql wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dog-blueprint" {...props}></Icon>
