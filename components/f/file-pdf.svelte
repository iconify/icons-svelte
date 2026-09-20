<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wjwt6xd6j.css';
import '../../css/o/okh9tubhv.css';
import '../../css/a/an5si8esz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="wjwt6xd6j"/><path clip-rule="evenodd" class="okh9tubhv"/><path class="an5si8esz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:file-pdf" {...props}></Icon>
