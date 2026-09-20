<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1x776i8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p1x776i8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:local-content-share-dark" {...props}></Icon>
