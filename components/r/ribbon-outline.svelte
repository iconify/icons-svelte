<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2lfpzbfh.css';
import '../../css/d/d5vledc_g.css';
import '../../css/o/o6nm72myp.css';
import '../../css/k/knv03ac5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="d2lfpzbfh"/><path class="d5vledc_g"/><path class="o6nm72myp"/><circle class="knv03ac5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:ribbon-outline" {...props}></Icon>
