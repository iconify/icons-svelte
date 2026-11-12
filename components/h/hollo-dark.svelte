<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxo_cab5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jxo_cab5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hollo-dark" {...props}></Icon>
