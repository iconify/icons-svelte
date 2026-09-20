<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5kgcga9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u5kgcga9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hitkeep-dark" {...props}></Icon>
