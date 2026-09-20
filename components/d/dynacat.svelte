<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_e7a256j.css';
import '../../css/v/vs4phpb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u_e7a256j"/><path class="vs4phpb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dynacat" {...props}></Icon>
