<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/i/ih_4ne4_y.css';
import '../../css/v/v8blxvper.css';
import '../../css/t/tjvl0_bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="ih_4ne4_y"/><path class="v8blxvper"/><path class="tjvl0_bwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:cake-two" {...props}></Icon>
