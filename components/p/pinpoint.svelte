<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qq0mz4bcs.css';
import '../../css/e/eabu6b49u.css';
import '../../css/n/n-_zbtbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="qq0mz4bcs"/><path clip-rule="evenodd" class="eabu6b49u"/><path clip-rule="evenodd" class="n-_zbtbbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:pinpoint" {...props}></Icon>
