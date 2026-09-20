<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hizec3bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hizec3bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adguardhome-sync-dark" {...props}></Icon>
