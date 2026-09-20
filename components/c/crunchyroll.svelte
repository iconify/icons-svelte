<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzb88qbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zzb88qbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crunchyroll" {...props}></Icon>
