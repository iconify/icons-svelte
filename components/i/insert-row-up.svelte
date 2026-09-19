<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rqg21wbtn.css';
import '../../css/h/hbbh8abmi.css';
import '../../css/p/p5f3lmg3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rqg21wbtn"/><path class="hbbh8abmi"/><path class="p5f3lmg3i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:insert-row-up" {...props}></Icon>
