<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v81t97bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v81t97bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amurex" {...props}></Icon>
