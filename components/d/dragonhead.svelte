<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1cffchus.css';
import '../../css/v/v5048sbmk.css';
import '../../css/n/n924abcqn.css';
import '../../css/a/aht29abkg.css';
import '../../css/n/ne73a8bqm.css';
import '../../css/b/bevi74bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e1cffchus"/><path class="v5048sbmk"/><path class="n924abcqn"/><path class="aht29abkg"/><path class="ne73a8bqm"/><path class="bevi74bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:dragonhead" {...props}></Icon>
