<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wf89k6buf.css';
import '../../css/n/n9vomcc2d.css';
import '../../css/n/nxbinb9me.css';
import '../../css/a/a4aenc4un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wf89k6buf"/><path class="n9vomcc2d"/><path class="nxbinb9me"/><path class="a4aenc4un"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:inbox-line-bold-duotone" {...props}></Icon>
