<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r3zcb7bmk.css';
import '../../css/r/revd7f9ko.css';
import '../../css/e/ej7kdi06a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r3zcb7bmk"/><path class="revd7f9ko"/><path clip-rule="evenodd" class="ej7kdi06a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-question-mark-outline" {...props}></Icon>
