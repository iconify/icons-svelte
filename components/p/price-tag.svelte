<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2lkqbxb.css';
import '../../css/k/kk12hpzil.css';
import '../../css/y/yx47hfbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="t_2lkqbxb"><path class="kk12hpzil"/><path class="yx47hfbsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:price-tag" {...props}></Icon>
