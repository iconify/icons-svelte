<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n2-9wig_g.css';
import '../../css/p/p1qq2rbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n2-9wig_g"/><path class="p1qq2rbrr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:briefcase-duotone" {...props}></Icon>
