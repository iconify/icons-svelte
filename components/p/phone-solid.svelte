<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwoahcb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gwoahcb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:phone-solid" {...props}></Icon>
