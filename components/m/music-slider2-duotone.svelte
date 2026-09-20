<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/ge4ttbaxi.css';
import '../../css/p/p1fwh-1ln.css';
import '../../css/u/u3vs50bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ge4ttbaxi"/><path clip-rule="evenodd" class="p1fwh-1ln"/><path class="u3vs50bgi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-slider2-duotone" {...props}></Icon>
