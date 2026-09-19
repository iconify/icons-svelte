<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne_11cc-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ne_11cc-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:diamond-three" {...props}></Icon>
