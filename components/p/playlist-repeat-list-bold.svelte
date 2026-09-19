<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4kr7db0h.css';
import '../../css/j/jor_1ib2e.css';
import '../../css/t/tdirdccsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="k4kr7db0h"><path class="jor_1ib2e"/><path class="tdirdccsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:playlist-repeat-list-bold" {...props}></Icon>
