<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/j/j4unv0bwc.css';
import '../../css/p/piqps_eog.css';
import '../../css/t/t3uk6hb6i.css';
import '../../css/h/hd26bt87f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="j4unv0bwc"/><path class="piqps_eog"/><path class="t3uk6hb6i"/><path class="hd26bt87f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:monetization-bill-magnet" {...props}></Icon>
