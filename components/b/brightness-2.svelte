<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj2pfiw1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="aj2pfiw1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:brightness-2" {...props}></Icon>
