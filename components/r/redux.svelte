<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v8n011b1s.css';
import '../../css/w/wa9dipq7e.css';
import '../../css/q/qkeylbb3s.css';
import '../../css/e/e07x1fbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="v8n011b1s"/><path class="wa9dipq7e"/><path class="qkeylbb3s"/><path class="e07x1fbkh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:redux" {...props}></Icon>
