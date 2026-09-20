<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5a8_trli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d5a8_trli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:modrinth" {...props}></Icon>
