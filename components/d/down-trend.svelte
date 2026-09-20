<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/c/cg0pfosfz.css';
import '../../css/a/a0j3wxb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="cg0pfosfz"/><path class="a0j3wxb9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:down-trend" {...props}></Icon>
