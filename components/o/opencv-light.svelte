<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/djqetsxsa.css';
import '../../css/l/ljxcg8b7i.css';
import '../../css/m/mrt9bwk2y.css';
import '../../css/c/cww-bgbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="djqetsxsa"/><path class="ljxcg8b7i"/><path class="mrt9bwk2y"/><path class="cww-bgbad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:opencv-light" {...props}></Icon>
