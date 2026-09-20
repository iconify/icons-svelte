<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ibhpxzb1a.css';
import '../../css/l/li59jccuh.css';
import '../../css/o/ozff5bcpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ibhpxzb1a"/><path class="li59jccuh"/><path clip-rule="evenodd" class="ozff5bcpp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bill2-duotone" {...props}></Icon>
