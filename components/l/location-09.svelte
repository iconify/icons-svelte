<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/o9c4bdc6w.css';
import '../../css/f/frli32bnn.css';
import '../../css/l/ljd34hyaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="o9c4bdc6w"/><path class="frli32bnn"/><path class="ljd34hyaq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:location-09" {...props}></Icon>
