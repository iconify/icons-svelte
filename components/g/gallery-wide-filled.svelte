<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s5g_42bun.css';
import '../../css/b/b0k0uuwhg.css';
import '../../css/n/neqh-tgow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s5g_42bun"/><path clip-rule="evenodd" class="b0k0uuwhg"/><path class="neqh-tgow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gallery-wide-filled" {...props}></Icon>
