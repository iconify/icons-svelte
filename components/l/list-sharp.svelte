<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxtqtcnph.css';
import '../../css/f/foequfu6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dxtqtcnph"/><path class="foequfu6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:list-sharp" {...props}></Icon>
