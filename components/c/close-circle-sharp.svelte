<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4kxclukv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f4kxclukv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:close-circle-sharp" {...props}></Icon>
