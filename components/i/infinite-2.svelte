<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlr2llxyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="rlr2llxyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:infinite-2" {...props}></Icon>
