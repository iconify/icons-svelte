<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/s/sichtzbah.css';
import '../../css/o/og-zvdzmo.css';
import '../../css/o/oto75skeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="sichtzbah"/><path class="og-zvdzmo"/><path class="oto75skeb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:clover" {...props}></Icon>
