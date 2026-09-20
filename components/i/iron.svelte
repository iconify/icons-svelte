<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fxyrw8bwp.css';
import '../../css/x/x7z9rul1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="fxyrw8bwp"/><path class="x7z9rul1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:iron" {...props}></Icon>
