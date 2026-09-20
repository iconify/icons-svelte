<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wysvl9k5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wysvl9k5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dozzle-light" {...props}></Icon>
