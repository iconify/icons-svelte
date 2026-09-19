<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/tzg6v5btu.css';
import '../../css/b/b2zbrybhm.css';
import '../../css/n/n5intik2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="tzg6v5btu"/><path class="b2zbrybhm"/><path class="n5intik2d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:adventure" {...props}></Icon>
