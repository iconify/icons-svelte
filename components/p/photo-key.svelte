<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/jz02cezfb.css';
import '../../css/c/ce48pvosb.css';
import '../../css/f/fada9bbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jz02cezfb"/><path class="ce48pvosb"/><path class="fada9bbso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:photo-key" {...props}></Icon>
