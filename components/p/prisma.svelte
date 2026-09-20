<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/az9ugz0fl.css';
import '../../css/g/gs7tczb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="az9ugz0fl"/><path clip-rule="evenodd" class="gs7tczb2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:prisma" {...props}></Icon>
