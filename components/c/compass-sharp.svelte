<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn3rdabgq.css';
import '../../css/n/nmv6y45kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="fn3rdabgq"/><path class="nmv6y45kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:compass-sharp" {...props}></Icon>
