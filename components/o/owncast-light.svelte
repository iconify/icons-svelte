<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa4mtmvgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xa4mtmvgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:owncast-light" {...props}></Icon>
