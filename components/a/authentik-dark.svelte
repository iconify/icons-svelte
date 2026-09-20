<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo2r4y9hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yo2r4y9hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:authentik-dark" {...props}></Icon>
