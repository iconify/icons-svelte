<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz01n2b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lz01n2b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:itch-io" {...props}></Icon>
