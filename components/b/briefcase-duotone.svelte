<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gn76a0bhm.css';
import '../../css/w/wsn7fvbhi.css';
import '../../css/k/kwdk_ccpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gn76a0bhm"/><path clip-rule="evenodd" class="wsn7fvbhi"/><path class="kwdk_ccpl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:briefcase-duotone" {...props}></Icon>
