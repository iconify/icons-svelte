<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hum31150c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hum31150c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:android-police-light" {...props}></Icon>
