<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/j/jn1bq4b3o.css';
import '../../css/r/ro85quuro.css';
import '../../css/l/lopkaybnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="jn1bq4b3o"/><path class="ro85quuro"/><path class="lopkaybnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:delivery-truck" {...props}></Icon>
