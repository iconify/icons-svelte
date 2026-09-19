<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c02b__imu.css';
import '../../css/h/hntgybcog.css';
import '../../css/n/nfows2ock.css';
import '../../css/p/p9-zrkb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGVndoHcZi" class="c02b__imu"/></defs><g class="hntgybcog"><path class="nfows2ock"/><path class="p9-zrkb4g"/><use href="#SVGVndoHcZi"/><use href="#SVGVndoHcZi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:emoji-sing-right" {...props}></Icon>
