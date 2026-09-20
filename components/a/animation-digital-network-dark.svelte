<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bexyg-fke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bexyg-fke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:animation-digital-network-dark" {...props}></Icon>
