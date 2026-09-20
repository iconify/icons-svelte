<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/palcawbql.css';
import '../../css/g/gsx79b0zp.css';
import '../../css/e/e6h2u9bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="palcawbql"/><path class="gsx79b0zp"/><path class="e6h2u9bam"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:inbox-in-filled" {...props}></Icon>
