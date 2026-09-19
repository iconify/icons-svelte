<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/p/pzsh4ib_v.css';
import '../../css/g/gd5p6sbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="pzsh4ib_v"/><path class="gd5p6sbdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:lockers" {...props}></Icon>
