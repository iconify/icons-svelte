<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzveq5_2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uzveq5_2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:camera-reverse-sharp" {...props}></Icon>
