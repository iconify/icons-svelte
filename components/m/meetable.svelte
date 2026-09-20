<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph5l2_t_x.css';
import '../../css/i/i70tju1pk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ph5l2_t_x"/><path class="i70tju1pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:meetable" {...props}></Icon>
