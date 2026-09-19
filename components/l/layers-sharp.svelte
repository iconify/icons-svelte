<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf1ibccow.css';
import '../../css/i/ikuuwzb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rf1ibccow"/><path class="ikuuwzb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:layers-sharp" {...props}></Icon>
