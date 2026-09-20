<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2lkqbxb.css';
import '../../css/d/d0koy98sj.css';
import '../../css/i/icu8aybza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="t_2lkqbxb"><path class="d0koy98sj"/><path class="icu8aybza"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:cart" {...props}></Icon>
