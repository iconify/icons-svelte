<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/k0juz0gib.css';
import '../../css/d/d4bpu0bvk.css';
import '../../css/j/jrp9cab6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="k0juz0gib"/><path class="d4bpu0bvk"/><path class="jrp9cab6c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:location-user-03" {...props}></Icon>
