<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/apv4jeb4k.css';
import '../../css/y/yhvfwbe3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="apv4jeb4k"/><path clip-rule="evenodd" class="yhvfwbe3i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:hazardous-outline-24px" {...props}></Icon>
