<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppv1d8b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ppv1d8b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freeshard-light" {...props}></Icon>
