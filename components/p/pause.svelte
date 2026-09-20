<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgmb2ablq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="fgmb2ablq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:pause" {...props}></Icon>
