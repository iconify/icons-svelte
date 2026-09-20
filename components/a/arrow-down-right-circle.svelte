<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/n64r6pb3k.css';
import '../../css/f/f0fk9cbko.css';
import '../../css/t/t69nndb1t.css';
import '../../css/x/xrgx2dblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="n64r6pb3k"/><path class="f0fk9cbko"/><path class="t69nndb1t"/><path class="xrgx2dblx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:arrow-down-right-circle" {...props}></Icon>
