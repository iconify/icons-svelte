<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/djqetsxsa.css';
import '../../css/i/it0-7sb5c.css';
import '../../css/e/etaocreys.css';
import '../../css/g/g287oqbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="djqetsxsa"/><path class="it0-7sb5c"/><path clip-rule="evenodd" class="etaocreys"/><path clip-rule="evenodd" class="g287oqbdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:aws-light" {...props}></Icon>
