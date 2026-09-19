<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk36stb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pk36stb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:person-sharp" {...props}></Icon>
