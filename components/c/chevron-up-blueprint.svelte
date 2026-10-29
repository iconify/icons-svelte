<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/o/ordx5ez8n.css';
import '../../css/k/ksulm8rer.css';
import '../../css/o/oh4nb-bcs.css';
import '../../css/z/zmpq0dbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ordx5ez8n wm-deco"/><path class="ksulm8rer wm-deco"/><path class="oh4nb-bcs"/><path class="zmpq0dbjk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevron-up-blueprint" {...props}></Icon>
