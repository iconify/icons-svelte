<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/u/uaumiac8d.css';
import '../../css/r/rxmld75-t.css';
import '../../css/f/fnryfbblz.css';
import '../../css/s/scgf5xban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="uaumiac8d"/><path class="rxmld75-t"/><path class="fnryfbblz"/><path class="scgf5xban"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:clapperboard" {...props}></Icon>
