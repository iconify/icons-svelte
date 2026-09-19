<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx8y2ds-k.css';
import '../../css/h/h2-2dgnfu.css';
import '../../css/j/jsmv-tewy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gx8y2ds-k"><path class="h2-2dgnfu"/><path class="jsmv-tewy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:align-horizontal-center" {...props}></Icon>
