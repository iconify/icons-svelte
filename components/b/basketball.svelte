<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/q/qgajy22ee.css';
import '../../css/f/fxn-nbfom.css';
import '../../css/v/vac8d1bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qgajy22ee"/><path class="fxn-nbfom"/><path class="vac8d1bao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:basketball" {...props}></Icon>
