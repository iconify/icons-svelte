<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu5b3g62n.css';
import '../../css/l/lkpw8_1oe.css';
import '../../css/n/nlnj0tdfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cu5b3g62n"/><path class="lkpw8_1oe"/><path class="nlnj0tdfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:arrowrightwardsupwards" {...props}></Icon>
