<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/c/c_r0j1b5k.css';
import '../../css/v/vwsljt4-n.css';
import '../../css/g/go52lxd2s.css';
import '../../css/a/a-tw77iau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="c_r0j1b5k"/><path class="vwsljt4-n"/><path class="go52lxd2s"/><path class="a-tw77iau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:checkmark-filled" {...props}></Icon>
