<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u05l21b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u05l21b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:9router-light" {...props}></Icon>
