<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a5jpz2bqs.css';
import '../../css/h/h4-tcib6f.css';
import '../../css/s/sgutr8bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a5jpz2bqs"/><path class="h4-tcib6f"/><path class="sgutr8bcc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-type-outline" {...props}></Icon>
