<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh5x32nps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kh5x32nps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:installatron-light" {...props}></Icon>
