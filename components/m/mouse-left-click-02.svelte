<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/vwfj18vvs.css';
import '../../css/v/v95kopftk.css';
import '../../css/n/neg6k6x2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="vwfj18vvs"/><path class="v95kopftk"/><circle class="neg6k6x2d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-left-click-02" {...props}></Icon>
