<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb2ayacaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rb2ayacaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:2fauth-dark" {...props}></Icon>
