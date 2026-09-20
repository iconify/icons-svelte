<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m2oyg21my.css';
import '../../css/h/heq1cwblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m2oyg21my"/><path class="heq1cwblt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-square-vert-duotone" {...props}></Icon>
