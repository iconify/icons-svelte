<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsi-k6tgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zsi-k6tgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crunchyroll-light" {...props}></Icon>
