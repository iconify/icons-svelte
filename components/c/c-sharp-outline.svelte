<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8x25ojnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w8x25ojnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:c-sharp-outline" {...props}></Icon>
