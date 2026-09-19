<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heq7cyb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="heq7cyb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:exit-sharp" {...props}></Icon>
