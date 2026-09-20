<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrflbhmmb.css';
import '../../css/h/h3j1xetuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xrflbhmmb"/><circle class="h3j1xetuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:livinity-dark" {...props}></Icon>
