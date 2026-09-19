<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lem80_bri.css';
import '../../css/e/e__bb0b3o.css';
import '../../css/g/g4__c4brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="lem80_bri"/><path class="e__bb0b3o"/><path clip-rule="evenodd" class="g4__c4brb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:plantation-worker-alt-outline" {...props}></Icon>
