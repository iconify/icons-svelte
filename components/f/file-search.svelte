<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l1gnxjbff.css';
import '../../css/p/p9_fnd36p.css';
import '../../css/p/p2kdwhbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l1gnxjbff"/><path class="p9_fnd36p"/><path class="p2kdwhbjk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-search" {...props}></Icon>
