<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ekkdwpuvf.css';
import '../../css/j/j203agb9e.css';
import '../../css/g/g440f-byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ekkdwpuvf"/><path clip-rule="evenodd" class="j203agb9e"/><path class="g440f-byn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:n8n-wordmark" {...props}></Icon>
