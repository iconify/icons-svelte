<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/f8tjsabrk.css';
import '../../css/v/voa5iabbp.css';
import '../../css/y/y4n7jxi2m.css';
import '../../css/s/sj8o4_b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f8tjsabrk"/><path class="voa5iabbp"/><path class="y4n7jxi2m"/><path class="sj8o4_b-d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:coins" {...props}></Icon>
