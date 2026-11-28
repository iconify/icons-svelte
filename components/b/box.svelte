<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/swm41ebxd.css';
import '../../css/r/rwtn5mbuu.css';
import '../../css/z/z8leietho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="swm41ebxd"/><path class="rwtn5mbuu"/><path class="z8leietho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:box" {...props}></Icon>
