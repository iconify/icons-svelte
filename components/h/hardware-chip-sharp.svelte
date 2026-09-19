<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np8f4rmpi.css';
import '../../css/h/haf9aeb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="np8f4rmpi"/><path class="haf9aeb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:hardware-chip-sharp" {...props}></Icon>
