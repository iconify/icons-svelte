<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/nv-adpsgj.css';
import '../../css/b/b2aw-grhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<g class="n1lsf0bnc"><path class="nv-adpsgj"/><path class="b2aw-grhr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:baseball" {...props}></Icon>
