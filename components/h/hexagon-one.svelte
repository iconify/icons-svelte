<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aotj56u1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aotj56u1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:hexagon-one" {...props}></Icon>
