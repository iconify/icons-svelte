<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o0n9q_5jv.css';
import '../../css/b/bate30btk.css';
import '../../css/r/r5k-ofblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="o0n9q_5jv"/><path class="bate30btk"/><path clip-rule="evenodd" class="r5k-ofblz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:file-dock-search-fill" {...props}></Icon>
