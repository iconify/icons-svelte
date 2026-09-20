<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n1yzn8b3d.css';
import '../../css/v/vkrhsz27r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":400};
const content = `<g class="ft5dv1b6b"><path class="n1yzn8b3d"/><path clip-rule="evenodd" class="vkrhsz27r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:miro-dark" {...props}></Icon>
