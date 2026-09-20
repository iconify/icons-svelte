<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it42j-b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="it42j-b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:recipesage-dark" {...props}></Icon>
