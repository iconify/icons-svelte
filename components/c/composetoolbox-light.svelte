<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmc3tccua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lmc3tccua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:composetoolbox-light" {...props}></Icon>
