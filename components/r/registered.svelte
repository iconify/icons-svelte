<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_weg3b7j.css';
import '../../css/r/rpvb-o6bq.css';
import '../../css/n/n9lhdyzbg.css';
import '../../css/w/wcwvfmbxf.css';
import '../../css/e/evlewacnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="j_weg3b7j"/><g class="rpvb-o6bq"><path clip-rule="evenodd" class="n9lhdyzbg"/><circle class="wcwvfmbxf"/><path clip-rule="evenodd" class="evlewacnw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:registered" {...props}></Icon>
