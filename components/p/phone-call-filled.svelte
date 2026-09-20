<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f9kfjgbxq.css';
import '../../css/q/q1y4cdbvh.css';
import '../../css/w/wd6v8jb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f9kfjgbxq"/><path class="q1y4cdbvh"/><path class="wd6v8jb0i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:phone-call-filled" {...props}></Icon>
