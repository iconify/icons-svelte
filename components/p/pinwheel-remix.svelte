<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgaj7hb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qgaj7hb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pinwheel-remix" {...props}></Icon>
