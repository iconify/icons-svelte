<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zyrm9ebma.css';
import '../../css/m/mzpm3frxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="zyrm9ebma"/><path class="mzpm3frxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:graphql-16" {...props}></Icon>
