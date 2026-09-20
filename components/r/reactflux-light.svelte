<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqjid6b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pqjid6b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reactflux-light" {...props}></Icon>
