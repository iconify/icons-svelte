<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zbp2-cc6v.css';
import '../../css/g/gow3njb7h.css';
import '../../css/r/re52utbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="zbp2-cc6v"/><path class="gow3njb7h"/><path class="re52utbdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:gulp" {...props}></Icon>
