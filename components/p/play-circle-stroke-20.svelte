<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noz2g8nyr.css';
import '../../css/r/r6f3racak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="noz2g8nyr"/><path class="r6f3racak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:play-circle-stroke-20" {...props}></Icon>
