<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu7p034nk.css';
import '../../css/b/b8kyosqzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nu7p034nk"/><path class="b8kyosqzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mermaid" {...props}></Icon>
