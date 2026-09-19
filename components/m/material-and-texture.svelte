<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/i6jo9jcep.css';
import '../../css/b/bxximwbyx.css';
import '../../css/m/mv-hq9vel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i6jo9jcep"/><path class="bxximwbyx"/><path class="mv-hq9vel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:material-and-texture" {...props}></Icon>
