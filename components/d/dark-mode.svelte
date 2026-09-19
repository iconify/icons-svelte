<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7g8vpbdo.css';
import '../../css/t/twovfhblf.css';
import '../../css/m/mu8tysbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l7g8vpbdo"><path class="twovfhblf"/><path class="mu8tysbrz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:dark-mode" {...props}></Icon>
