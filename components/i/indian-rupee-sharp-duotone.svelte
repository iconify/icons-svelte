<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqx5yqbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqx5yqbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:indian-rupee-sharp-duotone" {...props}></Icon>
