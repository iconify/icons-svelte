<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/pl-p6qb-v.css';
import '../../css/y/yisg2xf3a.css';
import '../../css/c/cq_-qoy2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="pl-p6qb-v"/><path class="yisg2xf3a"/><path class="cq_-qoy2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:megaphone" {...props}></Icon>
