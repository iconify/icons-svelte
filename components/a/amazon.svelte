<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-q5d1buo.css';
import '../../css/s/sfge3wiou.css';
import '../../css/y/y4c22ebjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f-q5d1buo"/><path clip-rule="evenodd" class="sfge3wiou"/><path class="y4c22ebjx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:amazon" {...props}></Icon>
