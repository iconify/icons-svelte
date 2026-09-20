<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sfybevbjo.css';
import '../../css/d/d4io04i0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sfybevbjo"/><path class="d4io04i0z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:inflight-duotone" {...props}></Icon>
