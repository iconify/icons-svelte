<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hseq8db_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hseq8db_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:enclosed-dark" {...props}></Icon>
