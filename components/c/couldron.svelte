<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/a/azvap9d7m.css';
import '../../css/l/l9q28cc9j.css';
import '../../css/a/ah8f13bnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="azvap9d7m"/><path class="l9q28cc9j"/><path class="ah8f13bnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:couldron" {...props}></Icon>
