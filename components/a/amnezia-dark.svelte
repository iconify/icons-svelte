<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to735iv_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="to735iv_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amnezia-dark" {...props}></Icon>
