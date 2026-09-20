<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb1wavm9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bb1wavm9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:atlasnode-dark" {...props}></Icon>
