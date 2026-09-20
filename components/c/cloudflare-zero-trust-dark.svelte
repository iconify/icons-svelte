<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9t4mnboc.css';
import '../../css/f/fr1kxcbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r9t4mnboc"/><path class="fr1kxcbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudflare-zero-trust-dark" {...props}></Icon>
