<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu6qz_i4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fu6qz_i4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docspell-dark" {...props}></Icon>
