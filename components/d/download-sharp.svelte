<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwtbtvbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kwtbtvbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:download-sharp" {...props}></Icon>
