<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbr-zzb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hbr-zzb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:play-fill-20" {...props}></Icon>
