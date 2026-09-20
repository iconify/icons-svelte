<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvz9b_w7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jvz9b_w7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:medialyze" {...props}></Icon>
