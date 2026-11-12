<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpbu6t_1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kpbu6t_1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:libretranslate" {...props}></Icon>
