<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n_sg2v3ed.css';
import '../../css/k/ke988s6ju.css';
import '../../css/c/cj-tp6byg.css';
import '../../css/j/jfytd4b0q.css';
import '../../css/c/cxr1s4b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n_sg2v3ed wm-k"/><path class="ke988s6ju wm-k"/><path class="cj-tp6byg wm-k"/><path class="jfytd4b0q wm-shine"/><path class="cxr1s4b7f wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-anime:check-circle" {...props}></Icon>
