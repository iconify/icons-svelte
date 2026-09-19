<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/ofg3t4b1p.css';
import '../../css/b/b64l0dbmf.css';
import '../../css/f/fj9t29bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ofg3t4b1p"/><path class="b64l0dbmf"/><path class="fj9t29bka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:rotate-camera-right" {...props}></Icon>
