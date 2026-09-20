<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2lkqbxb.css';
import '../../css/d/d0koy98sj.css';
import '../../css/r/rqube8b6r.css';
import '../../css/j/jin0lkpdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="t_2lkqbxb"><path class="d0koy98sj"/><path class="rqube8b6r"/><path class="jin0lkpdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:cart-remove" {...props}></Icon>
