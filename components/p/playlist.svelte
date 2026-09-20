<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h426v_b5r.css';
import '../../css/t/tcv195mym.css';
import '../../css/b/bolf66nom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h426v_b5r"/><path class="tcv195mym"/><path class="bolf66nom"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:playlist" {...props}></Icon>
