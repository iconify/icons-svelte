<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mekj18bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mekj18bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-contacts-dark" {...props}></Icon>
