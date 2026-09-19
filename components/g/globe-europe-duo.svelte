<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vk2uwtblc.css';
import '../../css/m/myo7tqb8f.css';
import '../../css/b/b59cqdtuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="vk2uwtblc"/><path clip-rule="evenodd" class="myo7tqb8f"/><path class="b59cqdtuz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-europe-duo" {...props}></Icon>
