<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlc5p2mlg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rlc5p2mlg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:bat" {...props}></Icon>
