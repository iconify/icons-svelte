<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/ggmykq2dj.css';
import '../../css/p/pa7amrb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ggmykq2dj"/><path class="pa7amrb5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:fact-check-duotone" {...props}></Icon>
