<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/bk4wim1-k.css';
import '../../css/p/pbtr10c0j.css';
import '../../css/w/w15cegb1z.css';
import '../../css/n/ngj96acjh.css';
import '../../css/o/o9th8x6rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="bk4wim1-k wm-deco"/><path class="pbtr10c0j wm-deco"/><path class="w15cegb1z wm-k"/><path class="ngj96acjh wm-a"/><path class="o9th8x6rw wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:factory-blueprint" {...props}></Icon>
