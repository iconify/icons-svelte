<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykk0mwkhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ykk0mwkhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:portainer-v1-dark" {...props}></Icon>
