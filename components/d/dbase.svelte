<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzsd_-k8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zzsd_-k8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:dbase" {...props}></Icon>
