<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtu_bi9-n.css';
import '../../css/p/puxz7qb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vtu_bi9-n"/><path class="puxz7qb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:restaurant-sharp" {...props}></Icon>
