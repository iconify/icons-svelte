<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/r2ofn9zof.css';
import '../../css/t/t07u0zb9p.css';
import '../../css/z/z5spejdbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="r2ofn9zof"/><path class="t07u0zb9p"/><path class="z5spejdbt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:basketball-hoop" {...props}></Icon>
