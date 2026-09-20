<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb8h1wbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bb8h1wbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pico-light" {...props}></Icon>
