<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_29rmlhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h_29rmlhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:color-fill-sharp" {...props}></Icon>
