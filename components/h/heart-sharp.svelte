<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh0svybfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bh0svybfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:heart-sharp" {...props}></Icon>
