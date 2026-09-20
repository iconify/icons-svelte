<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yq__4abaf.css';
import '../../css/t/t9r610bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yq__4abaf"/><path clip-rule="evenodd" class="t9r610bql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:calendar" {...props}></Icon>
