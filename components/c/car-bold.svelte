<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a0pcr2bht.css';
import '../../css/c/cx5-x2bsy.css';
import '../../css/v/v09ng3b3s.css';
import '../../css/n/nrbg57yne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a0pcr2bht"/><path class="cx5-x2bsy"/><path clip-rule="evenodd" class="v09ng3b3s"/><path class="nrbg57yne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:car-bold" {...props}></Icon>
