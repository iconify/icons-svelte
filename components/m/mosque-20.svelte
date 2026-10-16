<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glsz6lb6o.css';
import '../../css/l/lkhxdccgi.css';
import '../../css/d/d29tb6b3e.css';
import '../../css/t/t0vmepbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="glsz6lb6o"/><path class="lkhxdccgi"/><path class="d29tb6b3e"/><path class="t0vmepbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mosque-20" {...props}></Icon>
