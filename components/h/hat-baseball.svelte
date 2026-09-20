<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/c/cc-mb1skd.css';
import '../../css/i/i_z5bmbxi.css';
import '../../css/b/b_garkb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cc-mb1skd"/><path class="i_z5bmbxi"/><path class="b_garkb1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:hat-baseball" {...props}></Icon>
