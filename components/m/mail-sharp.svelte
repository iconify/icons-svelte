<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnckacb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nnckacb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:mail-sharp" {...props}></Icon>
