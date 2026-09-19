<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gf-vx5btw.css';
import '../../css/q/q_7vfqb-s.css';
import '../../css/b/bpg8_fb4j.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLoxIgeNb"><g class="ft5dv1b6b"><path class="gf-vx5btw"/><path class="q_7vfqb-s"/><path class="bpg8_fb4j"/></g></mask></defs><path mask="url(#SVGLoxIgeNb)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:doc-search" {...props}></Icon>
