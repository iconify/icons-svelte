<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsm4e0bue.css';
import '../../css/b/bu7uf3bkq.css';
import '../../css/p/p0z59inze.css';
import '../../css/x/x__xt5bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":59,"height":40};
const content = `<path class="rsm4e0bue"/><path class="bu7uf3bkq"/><path class="p0z59inze"/><path class="x__xt5bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:castopod" {...props}></Icon>
