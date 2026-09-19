<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a82rnzv4e.css';
import '../../css/n/nnyns4qoe.css';
import '../../css/e/e1njv-b-x.css';
import '../../css/c/cmk8cnb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a82rnzv4e"/><path class="nnyns4qoe"/><path clip-rule="evenodd" class="e1njv-b-x"/><path class="cmk8cnb6f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:antibody-outline-24px" {...props}></Icon>
