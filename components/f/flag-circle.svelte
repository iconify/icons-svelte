<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/psv_8pbss.css';
import '../../css/s/sq2md4utl.css';
import '../../css/o/o4nrtvbva.css';
import '../../css/a/anr8ncbxo.css';
import '../../css/k/kspoj7vnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="psv_8pbss"/><path class="sq2md4utl"/><path clip-rule="evenodd" class="o4nrtvbva"/><path clip-rule="evenodd" class="anr8ncbxo"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:flag-circle" {...props}></Icon>
