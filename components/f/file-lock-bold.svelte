<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cmta0755d.css';
import '../../css/b/b1hqolb1t.css';
import '../../css/k/klu756_3c.css';
import '../../css/c/c73t34bfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cmta0755d"/><path class="b1hqolb1t"/><path clip-rule="evenodd" class="klu756_3c"/><path class="c73t34bfn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-lock-bold" {...props}></Icon>
