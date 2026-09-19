<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fje1h4byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fje1h4byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:moon" {...props}></Icon>
