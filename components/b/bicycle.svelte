<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/k/kiy9nha1s.css';
import '../../css/u/uzn0bb4xh.css';
import '../../css/e/e4vh_8b-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kiy9nha1s"/><path class="uzn0bb4xh"/><path class="e4vh_8b-e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:bicycle" {...props}></Icon>
