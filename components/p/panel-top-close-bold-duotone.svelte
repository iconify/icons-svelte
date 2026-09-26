<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g1fz9lbxt.css';
import '../../css/s/sfju8cbdk.css';
import '../../css/n/n3if34fqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="g1fz9lbxt"/><path class="sfju8cbdk"/><path class="n3if34fqm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-top-close-bold-duotone" {...props}></Icon>
