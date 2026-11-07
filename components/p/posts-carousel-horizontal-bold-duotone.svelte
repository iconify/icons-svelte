<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtpeb-edw.css';
import '../../css/b/bjogh6b3n.css';
import '../../css/h/hlqi7zbwo.css';
import '../../css/i/inudikbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="bjogh6b3n"/><path class="hlqi7zbwo"/></g><path class="inudikbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:posts-carousel-horizontal-bold-duotone" {...props}></Icon>
