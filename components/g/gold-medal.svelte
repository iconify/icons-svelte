<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/v/vcir9ebrj.css';
import '../../css/j/ju4d0lblh.css';
import '../../css/c/civfl11di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="vcir9ebrj"/><path class="ju4d0lblh"/><path class="civfl11di"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:gold-medal" {...props}></Icon>
