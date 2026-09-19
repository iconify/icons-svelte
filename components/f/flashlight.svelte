<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/ceji5w1rd.css';
import '../../css/p/p94ddv79d.css';
import '../../css/g/gta12jdha.css';
import '../../css/e/eqmcb4bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ceji5w1rd"/><path class="p94ddv79d"/><path class="gta12jdha"/><path class="eqmcb4bzp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:flashlight" {...props}></Icon>
