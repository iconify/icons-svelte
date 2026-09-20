<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/k/k1r1gubki.css';
import '../../css/b/bp3h3heqa.css';
import '../../css/c/cj_0qhb1y.css';
import '../../css/f/fpwh461jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="k1r1gubki"/><path class="bp3h3heqa"/><path class="cj_0qhb1y"/><path class="fpwh461jy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:people" {...props}></Icon>
