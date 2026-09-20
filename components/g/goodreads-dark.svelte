<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu1_e0pru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uu1_e0pru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:goodreads-dark" {...props}></Icon>
