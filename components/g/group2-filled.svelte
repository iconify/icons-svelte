<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tb5ln68hg.css';
import '../../css/h/h28nogbso.css';
import '../../css/s/snrj8yb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tb5ln68hg"/><path class="h28nogbso"/><path class="snrj8yb8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:group2-filled" {...props}></Icon>
