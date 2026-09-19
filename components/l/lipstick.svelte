<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h6ucf0o2h.css';
import '../../css/n/nq7r8b9hk.css';
import '../../css/w/wh23c_bfb.css';
import '../../css/b/b5c417-ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="h6ucf0o2h"/><path class="nq7r8b9hk"/><path class="wh23c_bfb"/><path class="b5c417-ml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:lipstick" {...props}></Icon>
