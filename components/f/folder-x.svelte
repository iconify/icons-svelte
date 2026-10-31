<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t6f7kl7zy.css';
import '../../css/u/u1k-vk9af.css';
import '../../css/r/rt9v9sb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t6f7kl7zy wm-k"/><path class="u1k-vk9af wm-shine"/><path class="rt9v9sb0t wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:folder-x" {...props}></Icon>
