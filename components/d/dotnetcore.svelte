<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtropbt-f.css';
import '../../css/h/hal2ihy4e.css';
import '../../css/o/o42u20lrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="wtropbt-f"><path class="hal2ihy4e"/><path class="o42u20lrm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:dotnetcore" {...props}></Icon>
