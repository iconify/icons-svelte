<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly4bitb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ly4bitb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:libretranslate-dark" {...props}></Icon>
