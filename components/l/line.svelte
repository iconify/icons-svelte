<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q21hny20d.css';
import '../../css/m/mcr7zubuf.css';
import '../../css/s/s0l0zu_qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q21hny20d"/><path class="mcr7zubuf"/><path class="s0l0zu_qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:line" {...props}></Icon>
