<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/s/s-ayi5bku.css';
import '../../css/r/rxawnrbyo.css';
import '../../css/a/auzjo7sxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="s-ayi5bku"/><path class="rxawnrbyo"/><path class="auzjo7sxf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:atom" {...props}></Icon>
