<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjtlbw2qm.css';
import '../../css/d/dlomshbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":238.125,"height":238.125};
const content = `<circle class="bjtlbw2qm"/><path class="dlomshbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ladybird" {...props}></Icon>
