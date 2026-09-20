<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf6l_pbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mf6l_pbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pgadmin-light" {...props}></Icon>
