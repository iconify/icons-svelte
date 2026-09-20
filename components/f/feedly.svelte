<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8cz6n6-x.css';
import '../../css/r/r3b4dgb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q8cz6n6-x"/><path class="r3b4dgb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:feedly" {...props}></Icon>
