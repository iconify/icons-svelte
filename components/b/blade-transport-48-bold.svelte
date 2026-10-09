<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu9o71bva.css';
import '../../css/r/rudk7ubrf.css';
import '../../css/u/u2axsqyum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bu9o71bva"/><path class="rudk7ubrf"/><path class="u2axsqyum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blade-transport-48-bold" {...props}></Icon>
