<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e8t_k5p9z.css';
import '../../css/b/btq804b6i.css';
import '../../css/h/hw499ejxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="e8t_k5p9z"/><path class="btq804b6i"/><path class="hw499ejxi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:note-medical-duo" {...props}></Icon>
