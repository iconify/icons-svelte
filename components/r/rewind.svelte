<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nr46n3bws.css';
import '../../css/g/g8bi2fbze.css';
import '../../css/j/jpjexkb8q.css';
import '../../css/p/pviybjb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="nr46n3bws"/><path clip-rule="evenodd" class="g8bi2fbze"/><path class="jpjexkb8q"/><path clip-rule="evenodd" class="pviybjb8k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:rewind" {...props}></Icon>
