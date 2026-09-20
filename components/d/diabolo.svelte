<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/j1u9eup1x.css';
import '../../css/p/p1z6z8bfy.css';
import '../../css/e/e11g3ebpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j1u9eup1x"/><path class="p1z6z8bfy"/><path class="e11g3ebpc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:diabolo" {...props}></Icon>
