<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8fvisblt.css';
import '../../css/t/t-o-xlbsw.css';
import '../../css/p/pyphtmbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="n8fvisblt"/><path class="t-o-xlbsw"/><path class="pyphtmbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:pencil" {...props}></Icon>
