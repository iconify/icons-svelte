<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-7vtqbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x-7vtqbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qui-light" {...props}></Icon>
