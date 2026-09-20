<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/ulc51o2rw.css';
import '../../css/v/v0ls27beq.css';
import '../../css/n/n_wwbdbeo.css';
import '../../css/x/xeu9bf56s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ulc51o2rw"/><path class="v0ls27beq"/><path class="n_wwbdbeo"/><path class="xeu9bf56s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:modern-music-bass-guitar" {...props}></Icon>
