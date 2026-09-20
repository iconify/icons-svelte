<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydne_bc6v.css';
import '../../css/i/iwcyc_bei.css';
import '../../css/v/v_1d97bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ydne_bc6v"><path class="iwcyc_bei"/><path class="v_1d97bew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ai-generate-variation-spark" {...props}></Icon>
