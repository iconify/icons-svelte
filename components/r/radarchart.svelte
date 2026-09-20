<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjwka3mbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vjwka3mbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:radarchart" {...props}></Icon>
