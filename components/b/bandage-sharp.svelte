<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_jm4zc2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n_jm4zc2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bandage-sharp" {...props}></Icon>
