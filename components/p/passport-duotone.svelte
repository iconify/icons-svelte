<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b2cclbc5c.css';
import '../../css/s/sym4x4b5v.css';
import '../../css/f/fw-vshkfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b2cclbc5c"/><path clip-rule="evenodd" class="sym4x4b5v"/><path class="fw-vshkfs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:passport-duotone" {...props}></Icon>
