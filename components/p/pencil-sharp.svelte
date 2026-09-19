<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvgfvo2if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nvgfvo2if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:pencil-sharp" {...props}></Icon>
