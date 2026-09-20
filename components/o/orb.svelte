<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxu3wsb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rxu3wsb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:orb" {...props}></Icon>
