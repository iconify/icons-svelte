<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/if9l8bejy.css';
import '../../css/m/m0uafebbh.css';
import '../../css/e/eb8mxcbxa.css';
import '../../css/d/dsbbl1wrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="if9l8bejy"/><path class="m0uafebbh"/><path class="eb8mxcbxa"/><path class="dsbbl1wrr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:image-file-favorite-heart" {...props}></Icon>
