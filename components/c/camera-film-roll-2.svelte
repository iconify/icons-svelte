<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3xtuk_0z.css';
import '../../css/h/ha9__e8qz.css';
import '../../css/g/gsycjybkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="l3xtuk_0z"><path class="ha9__e8qz"/><path class="gsycjybkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:camera-film-roll-2" {...props}></Icon>
