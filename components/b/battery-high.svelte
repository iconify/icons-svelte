<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/k/kxwpge9gg.css';
import '../../css/w/wyiqk3bzv.css';
import '../../css/q/q75y0swvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kxwpge9gg"/><rect class="wyiqk3bzv"/><path class="q75y0swvu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:battery-high" {...props}></Icon>
