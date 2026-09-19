<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyexnnu5k.css';
import '../../css/r/rug9-jejd.css';
import '../../css/c/cm5ecor1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lyexnnu5k"/><path class="rug9-jejd"/><path class="cm5ecor1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:documents-sharp" {...props}></Icon>
