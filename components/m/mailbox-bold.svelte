<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/ootwnmxuy.css';
import '../../css/e/eyn1tubqg.css';
import '../../css/g/g68tbfbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ootwnmxuy"/><path class="eyn1tubqg"/><path class="g68tbfbgg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mailbox-bold" {...props}></Icon>
