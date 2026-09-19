<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/hhclp-bmx.css';
import '../../css/v/vwe9oyznd.css';
import '../../css/s/s71sv1b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="hhclp-bmx"/><path class="vwe9oyznd"/><path class="s71sv1b9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:hand-contactless" {...props}></Icon>
