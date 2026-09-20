<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de_dzzb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="de_dzzb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nitter-light" {...props}></Icon>
