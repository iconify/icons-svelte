<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgzdgcqyr.css';
import '../../css/j/jmo8dnbwh.css';
import '../../css/k/ki-cu7x0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hgzdgcqyr"/><path class="jmo8dnbwh"/><path class="ki-cu7x0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:haskell-wordmark" {...props}></Icon>
