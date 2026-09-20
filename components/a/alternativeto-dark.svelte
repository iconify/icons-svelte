<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj_ed3blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sj_ed3blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alternativeto-dark" {...props}></Icon>
