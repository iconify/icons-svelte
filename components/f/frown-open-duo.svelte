<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-ntwsbcy.css';
import '../../css/b/bzwehz--v.css';
import '../../css/a/a8924ab8w.css';
import '../../css/p/p20a_dbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f-ntwsbcy"/><path class="bzwehz--v"/><path class="a8924ab8w"/><path class="p20a_dbhv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:frown-open-duo" {...props}></Icon>
