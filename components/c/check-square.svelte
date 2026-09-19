<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/i/iwzi1nbxx.css';
import '../../css/h/h4l4yqvep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><rect class="iwzi1nbxx"/><path class="h4l4yqvep"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:check-square" {...props}></Icon>
