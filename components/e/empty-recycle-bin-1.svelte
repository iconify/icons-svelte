<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/n0jgj9b1n.css';
import '../../css/k/k64a2fhzl.css';
import '../../css/g/ghqnobbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="n0jgj9b1n"/><path class="k64a2fhzl"/><path class="ghqnobbvu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:empty-recycle-bin-1" {...props}></Icon>
