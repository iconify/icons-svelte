<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7f-sx8dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n7f-sx8dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:inoreader" {...props}></Icon>
