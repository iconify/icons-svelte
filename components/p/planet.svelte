<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/wr82iqbzm.css';
import '../../css/p/pj53ys2gt.css';
import '../../css/w/w08m7tbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="wr82iqbzm"/><path class="pj53ys2gt"/><path class="w08m7tbhl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:planet" {...props}></Icon>
