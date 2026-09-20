<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/c/cjqtb6rwi.css';
import '../../css/k/k5pymk42u.css';
import '../../css/j/jwawlch5e.css';
import '../../css/a/a4fp1owbq.css';
import '../../css/d/dz_ijegit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="cjqtb6rwi"/><path class="k5pymk42u"/><path class="jwawlch5e"/><path class="a4fp1owbq"/><path class="dz_ijegit"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:down-up" {...props}></Icon>
