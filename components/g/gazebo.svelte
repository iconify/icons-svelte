<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv1yczbez.css';
import '../../css/e/enk161xfw.css';
import '../../css/t/trgl4klpj.css';
import '../../css/a/aj84m6bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gv1yczbez"/><path class="enk161xfw"/><path class="trgl4klpj"/><path class="aj84m6bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gazebo" {...props}></Icon>
