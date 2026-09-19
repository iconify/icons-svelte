<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/hi9znkb4m.css';
import '../../css/c/cqf00f36x.css';
import '../../css/s/se4ujwtml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="hi9znkb4m"/><path class="cqf00f36x"/><path class="se4ujwtml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hand-bag-02" {...props}></Icon>
