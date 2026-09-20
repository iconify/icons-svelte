<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj7jzqbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pj7jzqbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jellyswarrm-light" {...props}></Icon>
