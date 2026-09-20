<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/su-ehlb8y.css';
import '../../css/a/alu2ms6-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":249,"height":33};
const content = `<g class="ft5dv1b6b"><path class="su-ehlb8y"/><path class="alu2ms6-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:colgate" {...props}></Icon>
