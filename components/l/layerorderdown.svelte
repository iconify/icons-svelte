<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwqla4h4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bwqla4h4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:layerorderdown" {...props}></Icon>
