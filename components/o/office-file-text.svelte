<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/evikbhbio.css';
import '../../css/t/th6z15lxd.css';
import '../../css/e/e-_y97b5b.css';
import '../../css/o/o0s61pf4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="evikbhbio"/><path class="th6z15lxd"/><path class="e-_y97b5b"/><path class="o0s61pf4c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:office-file-text" {...props}></Icon>
