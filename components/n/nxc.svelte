<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5hwqbklo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":343,"height":512};
const content = `<path class="x5hwqbklo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nxc" {...props}></Icon>
