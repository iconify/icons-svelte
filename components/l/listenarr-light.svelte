<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgkoy4z8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sgkoy4z8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:listenarr-light" {...props}></Icon>
