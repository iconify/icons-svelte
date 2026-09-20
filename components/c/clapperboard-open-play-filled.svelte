<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/phkyuccmo.css';
import '../../css/z/zwp75ob4l.css';
import '../../css/h/hv1qebcfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="phkyuccmo"/><path clip-rule="evenodd" class="zwp75ob4l"/><path class="hv1qebcfq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:clapperboard-open-play-filled" {...props}></Icon>
