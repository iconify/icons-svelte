<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gmeuf3gzy.css';
import '../../css/t/tvc4p7bak.css';
import '../../css/h/hiq63pbvw.css';
import '../../css/d/dtjpj4b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="gmeuf3gzy"/><path clip-rule="evenodd" class="tvc4p7bak"/><path clip-rule="evenodd" class="hiq63pbvw"/><path class="dtjpj4b_n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:laptop-cog" {...props}></Icon>
