<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxmb1c0no.css';
import '../../css/f/fr1kxcbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lxmb1c0no"/><path class="fr1kxcbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudflare-zero-trust-dark" {...props}></Icon>
