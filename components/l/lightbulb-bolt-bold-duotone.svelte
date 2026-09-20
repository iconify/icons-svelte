<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zgwtpp27u.css';
import '../../css/v/v26h66bss.css';
import '../../css/i/i5bmjjazl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zgwtpp27u"/><path class="v26h66bss"/><path class="i5bmjjazl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lightbulb-bolt-bold-duotone" {...props}></Icon>
