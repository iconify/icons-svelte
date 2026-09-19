<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swdppqbue.css';
import '../../css/e/e_lvdb_ov.css';
import '../../css/j/j7iar1btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="swdppqbue"/><path class="e_lvdb_ov"/><path class="j7iar1btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:karatelabs-wordmark" {...props}></Icon>
