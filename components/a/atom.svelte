<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/a/a8yocrbjl.css';
import '../../css/q/qbxa08-op.css';
import '../../css/d/dwzk6j57p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><ellipse transform="rotate(45)" class="a8yocrbjl"/><ellipse transform="rotate(315)" class="qbxa08-op"/><path class="dwzk6j57p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:atom" {...props}></Icon>
