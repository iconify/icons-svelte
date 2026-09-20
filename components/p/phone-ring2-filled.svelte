<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fdp0pfb0u.css';
import '../../css/j/jfquk0ace.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fdp0pfb0u"/><path clip-rule="evenodd" class="jfquk0ace"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:phone-ring2-filled" {...props}></Icon>
