<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/j/jsrzl-wng.css';
import '../../css/m/m8f5wpbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="jsrzl-wng"/><path class="m8f5wpbom"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:refresh-done-filled" {...props}></Icon>
