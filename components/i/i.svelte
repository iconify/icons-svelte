<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo_sdj8_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":1024};
const content = `<path class="fo_sdj8_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:i" {...props}></Icon>
