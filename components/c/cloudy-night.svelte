<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r4zl9wnja.css';
import '../../css/l/lqngvhr0v.css';
import '../../css/r/rj1kqxlid.css';
import '../../css/h/hbr7rrboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r4zl9wnja"/><path class="lqngvhr0v"/><path class="rj1kqxlid"/><path class="hbr7rrboq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cloudy-night" {...props}></Icon>
